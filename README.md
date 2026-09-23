# Hi, I'm Ivan 👋

I’m an MSc graduate in Artificial Intelligence.

My long-term research goal is to **understand and advance the
mathematical foundations of intelligence**.

I’m currently pursuing this through **AI interpretability** and
**representation geometry**, studying how internal representations
relate to reasoning and response correctness in language models.

## Current research

### Representation Geometry of LLM Responses

I’m extending my MSc thesis on the geometry of transformer hidden
states during correct and incorrect mathematical responses.

Using Phi-2 and GSM8K, I investigate differences in estimated
intrinsic dimension, the assumptions behind those measurements,
and the predictive information available in prefix representations.

My work includes:

- Comparing full-sequence and prefix representations.
- Auditing duplicate representations and numerical stability.
- Matching correct and incorrect attempts within problems.
- Evaluating leave-one-problem-out sensitivity.
- Controlling for length and simple formatting features.
- Investigating neighborhood size and same-problem grouping.
- Testing linear correctness prediction on held-out problems.

Recent experiments show that the positive pooled `pre_last`
intrinsic-dimension gap depends strongly on same-problem neighbors.
Excluding those neighbors reverses the late-layer average gap,
while count-matched random exclusion leaves it nearly unchanged.

Separately, linear probes extract correctness-related information
from prefix representations on held-out problems, outperforming
the tested length-and-formatting baseline.

These findings help distinguish properties of the representations
from effects of the measurement procedure. They do not establish
a causal reasoning mechanism.

[Explore the project →](https://github.com/IvMatic/llm-representation-geometry)

## Research direction

I’m interested in the mathematical principles underlying
representation, learning, and reasoning—and how understanding
those principles could inform improvements to intelligent systems.

My interests include:

- Mathematical foundations of intelligence
- Geometry of learned representations
- Mechanistic interpretability
- Reasoning dynamics in language models
- Causal interventions and their relevance to AI safety

## What I’m working toward

- Making my experiments reproducible from a fresh environment.
- Developing my MSc extension into a research paper.
- Preparing for PhD research.
- Building the mathematical and experimental skills needed
  for fundamental AI research.

## Connect

I’m interested in research collaborations, PhD opportunities,
and research engineering roles, particularly work connecting
mathematical ideas with careful empirical experiments.
