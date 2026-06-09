---
title: Auditable and Resource-Aware Intelligence (Saligrama Lab)
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
I study the foundations and systems needed to build, evaluate, and deploy AI under constraints: limited supervision, limited compute, limited communication, imperfect feedback, and uncertain ground truth.
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

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-section >}}
  Research Vision
{{< /hextra/hero-section >}}
</div>

Modern AI systems are no longer simple predictors trained and tested on fixed datasets. They reason over long contexts, use tools, produce open-ended outputs, interact with users, and are increasingly evaluated by other AI systems. This creates a central scientific challenge: **how do we learn, measure, and control intelligent systems when supervision, resources, and ground truth are all limited?**

My lab develops mathematical frameworks, algorithms, and evaluation protocols for this setting. A recurring theme is that AI systems should not only make predictions; they should also know when to compute, when to defer, when to seek evidence, when to communicate, when to verify, and when their measurements are unreliable.

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-section >}}
  Research Programs
{{< /hextra/hero-section >}}
</div>

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-section header="h3" >}}
  Auditable AI Evaluation and Ground Truth
{{< /hextra/hero-section >}}
</div>

We study the science of AI evaluation: how to measure AI systems, how to detect when those measurements are unreliable, and how to design protocols that make evaluation reproducible, diagnostic, and trustworthy.

Current work focuses on long-form factuality, AI judges, speech and multimodal evaluation, counterfactual audits, and evolving benchmarks. A central principle is that **ground truth is often a process, not a static dataset**: for complex AI outputs, reliable evaluation may require evidence, adjudication, revision, and versioning.

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-section header="h3" >}}
  Transformers, In-Context Learning, and Algorithm Discovery
{{< /hextra/hero-section >}}
</div>

We investigate when neural architectures learn algorithms rather than simply fit predictors. Recent work studies how trained transformers can implement recursive state updates and, in some settings, can be simplified into explicit iterative procedures for solving structured problems.

This line of work connects in-context learning, optimization, numerical linear algebra, representation geometry, and mechanistic understanding. The broader goal is to use trained architectures as a lens for discovering new algorithms and understanding how computation emerges from learned models.

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-section header="h3" >}}
  Constraint-Aware Learning and Inference
{{< /hextra/hero-section >}}
</div>

AI systems are deployed under operational constraints: computation is costly, communication is limited, labels are scarce, devices are heterogeneous, and errors have different consequences in different contexts. We develop algorithms that adapt to these constraints rather than ignoring them.

Topics include federated and distributed learning, adaptive inference, selective classification, test-time feature acquisition, hybrid edge/cloud inference, and budgeted decision-making. The goal is to build systems that can allocate computation, communication, supervision, and verification where they matter most.

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-section header="h3" >}}
  Learning with Limited Supervision and Open Worlds
{{< /hextra/hero-section >}}
</div>

A long-running theme in the lab is learning from limited, weak, or indirect supervision. We study how models generalize to new classes, new domains, and new modalities when labeled examples are scarce or absent.

Topics include zero-shot learning, few-shot learning, open-set recognition, cross-modal transfer, meta-learning, contextual reinforcement learning, and representation learning. This work asks how statistical structure, semantic information, and geometry can substitute for direct labels.

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-section header="h3" >}}
  Representation, Society, Graphs, and Networks
{{< /hextra/hero-section >}}
</div>

We also study how learned representations shape downstream behavior in social, scientific, and networked settings. This includes work on bias in machine-learned representations, subgraph anomaly detection, community detection, network change detection, and estimation on graphs.

Across these projects, the common objective is to understand how structure in data, networks, and representations affects learning, inference, and decision-making.

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-section >}}
  Selected Research Themes
{{< /hextra/hero-section >}}
</div>

- **Ground truth as a process:** evaluation for complex AI systems should support evidence, adjudication, auditing, and revision.
- **Evaluation as instrumentation:** aggregate accuracy is often insufficient; we need diagnostics that reveal why and where systems fail.
- **Transformers as algorithmic systems:** trained models can sometimes be understood by extracting the implicit procedures they implement.
- **Constraint-aware intelligence:** useful AI systems must decide how to allocate compute, communication, supervision, and verification under uncertainty.
- **Learning beyond labels:** models can exploit semantic, geometric, and structural information when direct supervision is limited.
