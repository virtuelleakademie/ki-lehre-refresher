# Computational theories of learning: A comparative review

This report examines several major theoretical frameworks for understanding learning and cognition, with particular attention to their computational foundations. The aim is to understand what each theory offers for thinking about how learners acquire the ability to solve complex problems, and how these theories relate to one another.

## 1. Cognitive Load Theory (CLT)

### Overview

Cognitive Load Theory was developed by John Sweller in the late 1980s. The core claim is simple: working memory has limited capacity, and instructional design should avoid overloading it. Learning involves acquiring *schemas*, organised knowledge structures stored in long-term memory that can be retrieved as single chunks, thereby reducing working memory demands.

CLT distinguishes three types of load:

- **Intrinsic load**: The inherent difficulty of the material, determined by *element interactivity* (how many elements must be processed simultaneously)
- **Extraneous load**: Load imposed by poor instructional design
- **Germane load**: Load devoted to schema construction (though this concept has fallen out of favour with CLT's creators)

### Key instructional effects

CLT has generated numerous empirically-validated effects:

- **Worked example effect**: Studying worked examples is more effective than problem-solving for novices
- **Split-attention effect**: Integrating multiple sources of information reduces load
- **Modality effect**: Using both visual and auditory channels increases effective capacity
- **Expertise reversal effect**: Techniques that help novices can hinder experts (Kalyuga et al., 2003)

The expertise reversal effect is particularly important: it shows that optimal instruction must be tailored to the learner's current knowledge state. Novices need guidance; experts need to generate.

### Computational status

CLT is *descriptive* rather than *computational*. It talks about schemas, load, and capacity, but does not specify:

- What a schema actually *is* (its internal structure)
- How schemas are constructed from experience
- How load is computed or measured
- The mechanisms by which schemas reduce load

Critics have noted that "there's no objective way to measure cognitive capacity and test the theory" and that CLT is "based on a vastly oversimplified and antiquated notion of 'working memory' that was current in psychology in the 1970s."

Despite these limitations, CLT's prescriptive value for instructional design is substantial. The question is whether a more computational foundation could sharpen its predictions and extend its scope.

### Sources

- [Cognitive Load Theory (InstructionalDesign.org)](https://www.instructionaldesign.org/theories/cognitive-load/)
- [Sweller (2011) chapter on CLT](https://www.emrahakman.com/wp-content/uploads/2024/10/Cognitive-Load-Sweller-2011.pdf)
- [Expertise Reversal Effect (Kalyuga 2007)](https://www.uky.edu/~gmswan3/EDC608/Kalyuga2007_Article_ExpertiseReversalEffectAndItsI.pdf)
- [CLT criticism (PMC)]()

---

## 2. ACT-R: Adaptive Control of Thought—Rational

### Overview

ACT-R is a *cognitive architecture* developed by John Anderson at Carnegie Mellon University. Unlike CLT, it is explicitly computational: a working simulation that can be programmed to perform cognitive tasks.

ACT-R distinguishes two types of knowledge:

- **Declarative knowledge**: Facts, represented as chunks in a semantic network
- **Procedural knowledge**: Skills, represented as production rules (IF-THEN statements)

### Skill acquisition in ACT-R

Anderson's theory of skill acquisition involves three stages:

1. **Declarative stage**: The learner has factual knowledge but must interpret it using general-purpose procedures. Performance is slow, effortful, and error-prone. Working memory load is high.

2. **Knowledge compilation**: Through practice, sequences of productions are *composed* into single productions, and declarative facts are *procedural*: they become embedded directly in productions. This is called *proceduralization*.

3. **Procedural/automatic stage**: Actions are performed by refined productions without conscious mediation. Performance is fast and automatic.

This progression mirrors what we earlier called "amortization": initially, the learner must generate solutions effortfully from declarative knowledge; with practice, this becomes compiled into efficient retrieval.

### Rational analysis

In the late 1980s, Anderson developed *rational analysis*: the idea that cognition is optimally adapted to the statistical structure of the environment. The methodology involves:

1. Specify the goals of the cognitive system
2. Model the environment's statistical structure
3. Derive the optimal behavioral function
4. Compare to empirical data

This provides a *normative* framework: what *should* the learner do, given environmental constraints? ACT-R's mechanisms are designed to approximate rational solutions.

### Educational applications

ACT-R has been the foundation for *intelligent tutoring systems*, most notably the cognitive tutors used in mathematics education. These tutors model the student's knowledge state and provide adaptive instruction. The Pittsburgh tutoring systems are "often cited as the most successful intelligent tutoring effort."

### Computational status

ACT-R is genuinely computational: it is implemented software that makes quantitative predictions. However, the "production rule" formalism may not capture the structure of generative models in the sense we discussed earlier. Productions are more like cached procedures than flexible generative processes.

### Sources

- [ACT-R official site](https://act-r.psy.cmu.edu/)
- [ACT-R Wikipedia](https://en.wikipedia.org/wiki/ACT-R)
- [Anderson (1982) Acquisition of Cognitive Skill](https://gwern.net/doc/iq/1982-anderson-2.pdf)
- [Rational Analysis (Wikipedia)](https://en.wikipedia.org/wiki/Rational_analysis)

---

## 3. Bayesian models of cognition

### Overview

The Bayesian approach, developed by researchers including Joshua Tenenbaum (MIT), Tom Griffiths (Princeton), and Noah Goodman (Stanford), models learning as *probabilistic inference*. The learner is assumed to have:

- A **hypothesis space**: the set of possible explanations for observed data
- **Prior probabilities**: beliefs about which hypotheses are likely before seeing data
- **Likelihood function**: how probable the data is under each hypothesis

Learning consists of computing the **posterior probability** of hypotheses given data, using Bayes' rule:

$$P(h|d) \propto P(d|h) \cdot P(h)$$

### Generative models

Crucially, the Bayesian framework assumes learners have *generative models*: internal representations of how data is produced. The likelihood function P(d|h) captures "if hypothesis h were true, how would the world generate data d?"

Learning is then *inverting* this generative model: given observed data, infer which hypothesis (which world-state) probably generated it.

### Hierarchical Bayesian models

A key extension is *hierarchical Bayesian models* (HBMs), where inference happens at multiple levels:

- Lower levels: specific hypotheses about particular situations
- Higher levels: abstract principles that constrain lower-level hypotheses

This provides a computational account of *learning to learn*: as you acquire experience, you learn not just specific facts but abstract structure that makes future learning faster.

A surprising result is the "blessing of abstraction": higher-level abstractions are sometimes acquired *before* lower-level details, because the hypothesis space at higher levels is smaller.

### Probabilistic programming

The computational implementation of these ideas uses *probabilistic programming languages* (e.g., WebPPL, Church). Programs express generative models, and inference algorithms compute posteriors. This allows precise specification of what learners are assumed to know and how they update.

### Program induction

Recent work (Lake, Salakhutdinov, Tenenbaum, 2015) models concept learning as *Bayesian program induction*: learners construct small programs that best explain observations. This achieves human-level performance on one-shot learning tasks and captures key features of human concept learning: compositionality, causality, and learning to learn.

### Computational status

Bayesian models are highly computational: they specify exact representations, inference algorithms, and make quantitative predictions. However, they are often computationally intractable (exact Bayesian inference is generally NP-hard), raising questions about psychological plausibility.

### Sources

- [Probabilistic Models of Cognition (probmods.org)](http://probmods.org/)
- [Griffiths & Tenenbaum - Bayesian models of cognition (PDF)](https://cocosci.princeton.edu/tom/papers/bayeschapter.pdf)
- [Bayesian models of cognition (MIT Press)](https://mitpress.mit.edu/9780262049412/bayesian-models-of-cognition/)
- [Human-level concept learning through probabilistic program induction (Science)](https://science.sciencemag.org/content/350/6266/1332.full)

---

## 4. Predictive processing and active inference

### Overview

Predictive processing (PP), developed by Karl Friston and others, proposes that the brain is fundamentally a *prediction machine*. The brain maintains a hierarchical generative model of the world and constantly generates predictions about incoming sensory signals.

### The free energy principle

Friston's *free energy principle* states that biological systems minimise *surprisal* (or its upper bound, free energy). In practical terms:

- The brain predicts sensory input
- Mismatches between prediction and reality generate *prediction errors*
- Learning updates the generative model to reduce future prediction errors
- Action changes the world to make predictions come true

### Precision weighting

A key concept is *precision*: the brain's estimate of how reliable a prediction error is. High-precision errors drive learning and attention; low-precision errors are ignored. Neuromodulators (dopamine, acetylcholine) are thought to encode precision.

### Learning in predictive processing

Learning occurs when predictions fail. The prediction error propagates up the hierarchy, updating expectations at each level. "Learning only occurs when events violate expectations—i.e., when they are surprising."

This directly connects to our earlier discussion: a student who copies AI solutions experiences no prediction errors, so no learning occurs. The struggle of attempting to generate and failing is precisely what drives model updating.

### Active inference

Active inference extends PP to action: agents act to minimise expected future prediction errors. This unifies perception, learning, and action under a single principle.

### Computational status

PP is highly computational, with explicit mathematical formulations (variational inference, message passing algorithms). However, it is primarily a theory of brain function rather than education, and translating its insights to instructional design is non-trivial.

### Educational implications

The Mind Brain Education community has begun exploring PP for education. Key insights:

- "Generative competence" means making accurate predictions in novel contexts
- Learning requires meaningful prediction errors
- Simply receiving correct answers doesn't update the model

### Sources

- [Free Energy Principle (Wikipedia)](https://en.wikipedia.org/wiki/Free_energy_principle)
- [Active inference and learning (PMC)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5167251/)
- [Predictive Processing and Education (Mind Brain Education)](https://www.mindbrained.org/october-2020-predictive-processing/)

---

## 5. Model-based vs model-free learning

### Overview

Computational neuroscience and reinforcement learning distinguish two learning systems:

- **Model-free learning**: Values are associated with actions through trial-and-error. The learner caches estimates of how good actions are without representing why.
- **Model-based learning**: The learner builds an internal model of the environment and uses it to simulate and plan.

### Trade-offs

Model-free learning is slow to acquire but fast to execute. It produces efficient, automatic behavior but is inflexible: if the environment changes, you must relearn from scratch.

Model-based learning is fast to acquire (any information about the environment can be incorporated) but slow to execute (requires simulation). It is flexible: changes in goals or environment can be immediately accommodated.

### Connection to amortization

This distinction maps directly onto our earlier discussion:

- **Model-based** = generating solutions from an internal model (slow, flexible, effortful)
- **Model-free** = retrieving cached values/procedures (fast, inflexible, automatic)

Amortization is the process by which model-based computations become compiled into model-free caches. With enough experience in a domain, you don't need to simulate; you can directly retrieve.

### Evidence for dual systems

Neuroimaging and behavioral experiments provide evidence that humans use both systems, with the balance depending on time pressure, cognitive load, and task structure. The prefrontal cortex is associated with model-based planning; the basal ganglia with model-free habit learning.

### Sources

- [The ubiquity of model-based reinforcement learning (Daw, Princeton)](https://www.princeton.edu/~ndaw/dsd12.pdf)
- [Model-based and model-free mechanisms (PMC)](https://pmc.ncbi.nlm.nih.gov/articles/PMC3570165/)
- [Neuromatch Academy tutorial](https://compneuro.neuromatch.io/tutorials/W3D4_ReinforcementLearning/student/W3D4_Tutorial4.html)

---

## 6. Amortized inference

### Overview

In machine learning, *amortized inference* refers to training a neural network to approximate Bayesian inference. Instead of running expensive inference algorithms for each new observation, you "amortize" the computational cost by learning a direct mapping from data to posterior.

The paradigm example is the *variational autoencoder* (VAE):

- An **encoder** (inference network) maps observations to latent representations
- A **decoder** (generative model) maps latent representations back to observations
- Training jointly optimizes both

### Relevance to learning

This provides a formal model for how "generation from the model" can become "efficient retrieval":

1. Initially, inference requires expensive computation (model-based)
2. With enough experience, a fast recognition network is trained (model-free)
3. The recognition network *approximates* what full inference would compute

The "amortization gap" is the difference between the fast approximation and the true posterior. This may correspond to cases where cached procedures fail to generalise.

### Sources

- [Amortized Variational Inference overview (Medium)](https://sertiscorp.medium.com/amortized-variational-inference-an-overview-f246c1e11e11)
- [Neural Methods for Amortized Inference (Annual Reviews)](https://www.annualreviews.org/content/journals/10.1146/annurev-statistics-112723-034123)
- [Deep Amortized Inference for Probabilistic Programs (Stanford)](https://cocolab.stanford.edu/papers/daipptr.pdf)

---

## 7. Synthesis: Towards a computational view of learning to solve problems

### The framework emerging from our discussion

Combining these perspectives, we can sketch a computational view of learning:

**1. The learner acquires a generative model**

The learner builds an internal model that captures how the domain works: causal relationships, constraints, and regularities. In physics, this means understanding how circuits behave, how oscillators work, why superposition applies.

This corresponds to:

- Schema acquisition (CLT)
- Declarative knowledge (ACT-R)
- Hypothesis space / prior structure (Bayesian models)
- The generative model (predictive processing)
- The world model (model-based learning)

**2. The learner uses the generative model to solve problems**

Given a novel problem, the learner runs their internal model: simulating, deriving, generating a solution path. This is effortful and slow but flexible.

This corresponds to:

- Working memory engagement (CLT)
- Interpretive application of declarative knowledge (ACT-R)
- Posterior inference (Bayesian models)
- Prediction and prediction error (predictive processing)
- Model-based planning (RL)

**3. With practice, solutions become amortized**

Repeated generation for similar problems builds fast recognition: the learner can directly produce solutions without full simulation.

This corresponds to:

- Schema automation (CLT)
- Proceduralization / knowledge compilation (ACT-R)
- Amortized inference (Bayesian/ML)
- Precision-weighted predictions becoming automatic (PP)
- Model-free habits (RL)

### What does this mean for instruction?

**Stage 1: Build the generative model**

The learner needs to acquire the underlying model of the domain. This requires:

- Explicit instruction on concepts, principles, causal structure
- Self-explanation of worked examples (running one's model against the solution)
- Feedback that highlights where predictions diverge from reality

Worked examples help *if* the learner actively engages their developing model. Passive observation provides data but doesn't drive inference.

**Stage 2: Practice generation**

Once the model exists, the learner needs to exercise it: attempting problems, generating solutions, experiencing prediction errors, refining the model.

The expertise reversal effect makes sense here: once you have the model, guidance becomes redundant. You need to generate.

**Stage 3: Amortize**

With varied practice, frequently-needed generation paths become compiled into fast retrieval. The expert recognizes problem types and produces solutions efficiently.

But amortization without the underlying model is brittle: it works only for familiar patterns. The student who has "learned" by copying AI solutions has neither the generative model nor valid amortization.

### The AI risk, computationally stated

When students use AI to get solutions:

1. They receive answers without generating predictions, so no prediction errors occur
2. The generative model is not updated (no learning in the PP sense)
3. They may memorize solutions, but this is pure caching without an underlying model
4. The cached solutions don't generalise because they're not connected to a model of *why*

The student ends up with model-free habits that lack a model-based foundation. This is the worst of both worlds: the inflexibility of cached procedures without the generative capacity to handle novelty.

### Open questions

1. **How do we help students build the generative model?** What instructional techniques most effectively support model construction (not just parameter estimation within a known model structure)?

2. **How do we know when the model is ready?** The expertise reversal effect says guidance should fade as expertise grows. But how do we assess when a student's model is sufficient for productive generation?

3. **Can AI be used to support model-building rather than bypass it?** Could AI systems be designed to elicit predictions, generate targeted feedback, and provide scaffolded generation rather than complete solutions?

4. **What is the relationship between CLT's "element interactivity" and the complexity of the generative model?** High element interactivity might correspond to models with many interacting components that must be simulated simultaneously.

---

## 8. Reframing CLT effects in Bayesian terms

The instructional effects discovered by CLT researchers are empirically robust, but their theoretical explanations invoke vague notions of "load" and "capacity." A Bayesian reframing can sharpen these explanations and generate novel predictions.

### Split-attention effect

**CLT version**: When information is split across multiple sources (e.g., diagram + separate text), learners must mentally integrate them, consuming working memory.

**Bayesian reframing**: The learner must infer not just the domain content but also the *mapping structure* between sources. With integrated materials, the relational structure (how text corresponds to diagram) is given explicitly. With split materials, the learner must perform additional inference to discover this structure. This is an extra inference problem layered on top of learning the domain content itself.

The Bayesian framing predicts that split attention effects should be reduced if the relational structure is made explicit even without physical integration (e.g., "the labels A, B, C in the text correspond to positions A, B, C in the diagram").

### Redundancy effect

**CLT version**: When identical information appears in multiple formats unnecessarily (e.g., spoken narration + identical on-screen text), it hurts learning because both must be processed.

**Bayesian reframing**: Redundant information provides no additional evidence for updating beliefs. The likelihood P(data|hypothesis) is unchanged whether you observe the same fact once or twice. However, if the redundancy is *unexpected*, the learner may initially treat both sources as potentially distinct, wasting inference effort trying to determine why there are two sources and whether they contain different information.

**Expected vs unexpected redundancy**: This analysis suggests that redundancy is harmful primarily when it is *surprising*. If the learner knows in advance that the narration will exactly match the on-screen text, they can efficiently ignore one channel. No inference is wasted searching for differences that don't exist.

This generates a testable prediction: explicitly telling learners "the audio will match the text exactly" should eliminate or substantially reduce the redundancy effect. The original CLT experiments likely did not control for this, so learners had to discover the redundancy themselves.

More generally: information that confirms what you already confidently believe provides minimal evidence for model updating. This is not "wasted capacity" but simply the mathematics of Bayesian inference. The problem arises only when you don't know in advance that the information will be redundant.

### Modality effect

**CLT version**: Using both visual and auditory channels increases effective working memory capacity.

**Bayesian reframing**: Different sensory channels provide *conditionally independent* evidence about the same underlying content. Two independent observations narrow the posterior distribution faster than two correlated observations. This is not about "more capacity" but about the statistical properties of evidence aggregation.

If you hear a concept explained while simultaneously seeing a complementary diagram, you have two partially independent sources of evidence about the underlying structure. The posterior after observing both is more concentrated than after observing either alone. This is standard Bayesian evidence combination.

### Worked example effect

**CLT version**: Worked examples reduce cognitive load compared to problem-solving because the learner doesn't need to search for solutions.

**Bayesian reframing**: Worked examples provide *supervised* training data: the learner observes both the problem and the complete solution path. This is maximally informative for updating beliefs about which procedures are correct and when they apply.

Problem-solving without feedback provides only sparse information: you discover whether your final answer is right or wrong, but not which steps were correct or why. The likelihood function P(outcome|procedure) is much less informative than P(complete solution path|procedure).

From a Bayesian perspective, worked examples are efficient because they provide high-bandwidth evidence about the generative process that produces correct solutions.

### Expertise reversal effect

**CLT version**: Techniques that help novices become redundant or harmful for experts because experts already have schemas.

**Bayesian reframing**: Experts have strong priors: their posterior beliefs are already concentrated on correct hypotheses. Additional evidence (guidance, worked examples) provides diminishing returns for updating an already-concentrated posterior.

Worse, for experts, detailed guidance may constitute *expected* information that provides no learning signal. An expert studying a worked example already knows what each step will be. There is no surprise, no belief updating, no learning.

For novices, the same worked example is *unexpected*: each step provides information that updates their diffuse prior. The same instructional material has different information content depending on the learner's prior knowledge.

This explains why experts benefit from problem-solving: generating solutions produces opportunities for their predictions to be wrong. Even experts occasionally make errors or discover edge cases. Problem-solving generates the unexpected outcomes that drive belief updating, while worked examples (for experts) generate only expected confirmations.

### Element interactivity as inference complexity

**CLT version**: High element interactivity means many elements must be processed simultaneously because they depend on each other. This increases intrinsic cognitive load.

**Bayesian reframing**: Element interactivity corresponds to the *density of dependencies* in the inference problem. Consider knowledge as a graphical model: variables (concepts, quantities) connected by dependency relationships.

- **Low interactivity**: Variables are mostly independent. The inference problem *factorizes* into independent sub-problems. You can infer each variable separately and combine the results. Computationally tractable.

- **High interactivity**: Variables are densely connected. To infer the state of any one variable, you must consider the states of many others simultaneously. The problem does not decompose. Computationally expensive (potentially NP-hard in the worst case).

**Working memory as inference buffer**: In this view, working memory is not a container with a fixed number of "slots" but a computational buffer for holding the variables involved in a single inference step. If the inference factorizes, you can process sequentially: infer one variable, commit the result to long-term memory, proceed to the next. If it doesn't factorize, you must hold multiple variables simultaneously while computing their joint posterior.

The capacity limit is not about "number of items" but about the *size of inference problems* that can be solved in a single pass.

**Schemas as learned factorizations**: A schema, in this framing, is a *learned factorization* of a previously high-interactivity problem. Once you have chunked "series resistors" into a single unit with known composite behavior, you've reduced the number of variables in play. The internal complexity of the chunk is handled by the schema; only its external interface participates in ongoing inference.

Expertise, then, means possessing schemas that make objectively high-interactivity problems *subjectively* low-interactivity by providing useful factorizations.

### Summary: CLT effects as properties of Bayesian inference

| CLT concept | Bayesian interpretation |
|-------------|------------------------|
| Working memory load | Size of the inference problem that must be solved jointly |
| Element interactivity | Density of dependencies in the graphical model |
| Schema | A learned factorization that chunks interacting variables |
| Intrinsic load | Irreducible inference complexity of the domain structure |
| Extraneous load | Unnecessary inference (e.g., inferring structure that could have been given) |
| Split attention | Additional inference required to discover cross-source mappings |
| Redundancy | Wasted inference when redundancy is unexpected; harmless when expected |
| Modality effect | Benefit of conditionally independent evidence sources |
| Worked example effect | High-bandwidth supervised evidence vs. sparse outcome feedback |
| Expertise reversal | Diminishing information value for concentrated priors |

### Instructional implications

1. **Reduce unnecessary inference**: Make structure explicit rather than requiring learners to infer it. This includes relational mappings (split attention), the presence of redundancy, and hierarchical organization.

2. **Provide informative evidence**: Worked examples are effective because they provide complete solution paths, not just outcomes. Design instruction to maximize the information content of each observation.

3. **Calibrate to prior knowledge**: The same material has different information content for different learners. Novices need evidence that updates diffuse priors; experts need opportunities for unexpected outcomes.

4. **Build useful factorizations**: Teach chunks that encapsulate frequently-occurring patterns of interaction. Sequence instruction so that components with fewer dependencies are mastered first, becoming available as schemas for later, more complex material.

5. **Generate, don't just observe**: For learning to occur, the learner must make predictions that can be confirmed or violated. Passive observation of expected information produces no belief updating.

---

## References

### Cognitive Load Theory

- Sweller, J. (1988). Cognitive load during problem solving: Effects on learning. *Cognitive Science*, 12(2), 257-285.
- Kalyuga, S. et al. (2003). The expertise reversal effect. *Educational Psychologist*, 38(1), 23-31.

### ACT-R

- Anderson, J. R. (1982). Acquisition of cognitive skill. *Psychological Review*, 89(4), 369-406.
- Anderson, J. R. (1990). *The Adaptive Character of Thought*. Lawrence Erlbaum.

### Bayesian Models

- Tenenbaum, J. B., Kemp, C., Griffiths, T. L., & Goodman, N. D. (2011). How to grow a mind: Statistics, structure, and abstraction. *Science*, 331(6022), 1279-1285.
- Griffiths, T. L., Kemp, C., & Tenenbaum, J. B. (2008). Bayesian models of cognition. In R. Sun (Ed.), *Cambridge Handbook of Computational Cognitive Science*.

### Predictive Processing

- Clark, A. (2013). Whatever next? Predictive brains, situated agents, and the future of cognitive science. *Behavioral and Brain Sciences*, 36(3), 181-204.
- Friston, K. (2010). The free-energy principle: a unified brain theory? *Nature Reviews Neuroscience*, 11(2), 127-138.

### Model-based and Model-free Learning

- Daw, N. D., Niv, Y., & Dayan, P. (2005). Uncertainty-based competition between prefrontal and dorsolateral striatal systems for behavioral control. *Nature Neuroscience*, 8(12), 1704-1711.

### Amortized Inference

- Kingma, D. P., & Welling, M. (2014). Auto-encoding variational bayes. *ICLR*.
- Ritchie, D. et al. (2016). Deep amortized inference for probabilistic programs. *arXiv preprint*.
