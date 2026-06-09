---
title: Venkatesh Saligrama
toc: false
layout: hextra-home
navbar:
  showTitle: false
---

{{< hextra/hero-container
  image="/img/profile-photo.jpg"
  imageClass="hx-block hx-overflow-hidden hx-rounded-2x1"
  imageWidth="300" imageHeight="300"
  imageTitle="Venkatesh Saligrama"
>}}
<div class="hx-mt-12 hx-mb-6">
{{< hextra/hero-headline >}}
  Venkatesh Saligrama
{{< /hextra/hero-headline >}}
</div>

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-subtitle >}}
  **Professor of Electrical and Computer Engineering, Boston University · Amazon Scholar**
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-subtitle >}}
Department of Electrical and Computer Engineering

Department of Computer Science (by courtesy)

8 St. Mary's Street, Room 438, Boston University, MA 02215

{{< icon "mail" >}} **srv@bu (add dot edu)**
{{< /hextra/hero-subtitle >}}
</div>
{{< /hextra/hero-container >}}

# Research Vision

Modern AI systems operate under fundamental constraints. Data are limited, labels are expensive, computation is finite, communication is costly, and evaluation is often imperfect. Yet these systems are increasingly expected to make reliable decisions, reason over complex information, and interact with people and other AI systems.

My research develops the foundations and systems needed to learn, reason, and evaluate under such constraints. We combine ideas from machine learning, statistical inference, optimization, and AI evaluation to understand how intelligent systems can make effective use of limited information, resources, and feedback.

A recurring theme across my work is that intelligence is not simply about prediction. It is also about deciding what information to acquire, what computation to perform, how to communicate, and when a conclusion should be trusted.

# Current Research Programs

## AI Evaluation, Auditing, and Ground Truth

As AI systems become more capable, evaluation itself is becoming a scientific challenge. Benchmarks saturate, expert labels disagree, and many outputs require evidence-based adjudication rather than simple annotation.

Our recent work studies how to construct reliable evaluations for long-form reasoning systems, AI judges, and multimodal agents. We develop protocols for auditing evaluation procedures, identifying failure modes, and building benchmarks whose ground truth can evolve as evidence accumulates.

**Representative work**

- DeepFact: Co-Evolving Benchmarks and Agents for Deep Research Factuality
- TRACE: Counterfactual Audits for Audio-Language Judges
- Evaluation protocols for AI judges and long-form factuality assessment

## Learning and Reasoning Under Constraints

Many real-world systems must operate with limited computation, communication, memory, or supervision.

We develop algorithms that adapt to these constraints rather than ignoring them. Applications include federated learning, distributed optimization, adaptive inference, selective classification, and hybrid cloud-edge systems.

**Representative work**

- FedDyn: Federated Learning Based on Dynamic Regularization
- Adaptive Neural Networks for Efficient Inference
- Test-Time Feature Acquisition and Budgeted Learning
- Selective Classification and Hybrid Inference

## Learning Beyond Direct Supervision

Humans often learn with little direct supervision. AI systems should be able to do the same.

Our work studies learning when labels are scarce, indirect, weak, or entirely absent. We investigate how semantic structure, contextual information, and prior knowledge can support generalization beyond observed training examples.

**Representative work**

- Zero-Shot Learning via Semantic Similarity Embedding
- Few-Shot and Open-Set Recognition
- Cross-Modal Transfer Learning
- Meta-Learning and Contextual Reinforcement Learning

## Neural Computation and Algorithm Discovery

Why do modern neural architectures work, and what computations do they learn?

Our recent work investigates transformers and in-context learning from an algorithmic perspective. Rather than viewing neural networks solely as predictors, we study when trained architectures implement identifiable computational procedures and how those procedures emerge from data and optimization.

**Representative work**

- Linear Transformers Implicitly Learn Numerical Algorithms
- In-Context Learning and Recursive State Updates
- Geometry and Token Selection in Large Language Models

## Learning on Networks and Structured Data

Many scientific, social, and technological systems are naturally represented as graphs and networks.

We develop methods for inference, anomaly detection, community discovery, and change detection on structured data.

**Representative work**

- Subgraph Anomaly Detection
- Community Detection
- Network Change Detection
- Statistical Learning on Graphs

# Selected Themes

- Learning with limited information
- Decision-making under resource constraints
- Evaluation under uncertainty
- Structure and geometry in representations
- Understanding computation in learned systems

> How can intelligent systems learn, reason, and be reliably evaluated when information, resources, and ground truth are inherently limited?
