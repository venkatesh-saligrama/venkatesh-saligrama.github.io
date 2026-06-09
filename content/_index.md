---
title: Machine Learning, AI Evaluation, and Intelligent Systems
toc: false
layout: hextra-home
navbar:
  showTitle: false
---

{{< hextra/hero-container
  image="/img/profile-photo.jpg"
  imageClass="hx-block hx-overflow-hidden hx-rounded-2x1"
  imageWidth="280" imageHeight="280"
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
I study how AI systems learn, reason, and are evaluated under constraints: limited supervision, limited resources, imperfect feedback, and uncertain ground truth.
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

<div class="hx-mt-8 hx-mb-6">
{{< hextra/hero-section >}}
  Research Vision
{{< /hextra/hero-section >}}
</div>

Modern AI systems are increasingly expected to reason over long contexts, use tools, interact with people, and evaluate other AI systems. This creates a basic scientific challenge: **how do we learn, measure, and control intelligent systems when supervision, resources, and ground truth are limited?**

My lab develops mathematical frameworks, algorithms, and evaluation protocols for this setting. A recurring theme is that intelligent systems should not only make predictions; they should also decide what information to acquire, what computation to perform, when to communicate, when to verify, and when a conclusion should be trusted.

<div class="hx-mt-8 hx-mb-6">
{{< hextra/hero-section >}}
  Research Programs
{{< /hextra/hero-section >}}
</div>

<div class="hx-mt-6 hx-mb-4">
{{< hextra/hero-section header="h3" >}}
  AI Evaluation, Auditing, and Ground Truth
{{< /hextra/hero-section >}}
</div>

We study how to evaluate AI systems when outputs are long-form, evidence-dependent, multimodal, or judged by other AI systems. Current work focuses on evolving benchmarks, AI judges, factuality evaluation, speech evaluation, and counterfactual audits.

**Selected papers:**  
[DeepFact: Co-Evolving Benchmarks and Agents for Deep Research Factuality](https://arxiv.org/abs/2603.05912) ·
[Hearing Between the Lines: Unlocking the Reasoning Power of LLMs for Speech Evaluation](https://aclanthology.org/2026.findings-eacl.151/)

<div class="hx-mt-6 hx-mb-4">
{{< hextra/hero-section header="h3" >}}
  Transformers, In-Context Learning, and Algorithm Discovery
{{< /hextra/hero-section >}}
</div>

We investigate when neural architectures learn algorithms rather than only fit predictors. Recent work studies transformers and in-context learning from an algorithmic perspective, asking when trained models can be simplified into explicit computational procedures.

**Selected papers:**  
[Linear Transformers Implicitly Discover Unified Numerical Algorithms](https://arxiv.org/abs/2509.19702)

<div class="hx-mt-6 hx-mb-4">
{{< hextra/hero-section header="h3" >}}
  Learning and Inference Under Constraints
{{< /hextra/hero-section >}}
</div>

Many AI systems must operate with limited computation, communication, memory, or supervision. We develop methods that adaptively allocate scarce resources while maintaining reliability and performance.

**Selected papers:**  
[Federated Learning Based on Dynamic Regularization](https://openreview.net/forum?id=B7v4QMR6Z9w) ·
[Adaptive Neural Networks for Efficient Inference](https://proceedings.mlr.press/v70/bolukbasi17a.html) ·
[Adaptive Classification for Prediction Under a Budget](https://proceedings.neurips.cc/paper/2017/hash/d9ff90f4000eacd3a6c9cb27f78994cf-Abstract.html)

<div class="hx-mt-6 hx-mb-4">
{{< hextra/hero-section header="h3" >}}
  Learning Beyond Direct Supervision
{{< /hextra/hero-section >}}
</div>

A long-running theme in the lab is learning from limited, weak, or indirect supervision. We study how semantic structure, contextual information, and representation geometry support generalization to new classes, domains, and modalities.

**Selected papers:**  
[Zero-Shot Learning via Semantic Similarity Embedding](https://arxiv.org/abs/1509.04767) ·
[Zero-Shot Learning via Joint Latent Similarity Embedding](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Zhang_Zero-Shot_Learning_via_CVPR_2016_paper.html) ·
[Learning Classifiers for Target Domain with Limited or No Labels](https://proceedings.mlr.press/v97/zhu19d.html)

<div class="hx-mt-6 hx-mb-4">
{{< hextra/hero-section header="h3" >}}
  Representations, Society, Graphs, and Networks
{{< /hextra/hero-section >}}
</div>

We study how structure in data, networks, and representations affects learning, inference, and decision-making. This includes work on bias in machine-learned representations, anomaly detection, community detection, network change detection, and graph-based estimation.

**Selected papers:**  
[Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings](https://papers.nips.cc/paper_files/paper/2016/hash/a486cd07e4ac3d270571622f4f316ec5-Abstract.html) ·
[Local Anomaly Detection](https://proceedings.mlr.press/v22/saligrama12.html) ·
[Video Anomaly Detection Based on Local Statistical Aggregates](https://blogs.bu.edu/srv/files/2012/04/cvpr_final.pdf)

<div class="hx-mt-8 hx-mb-6">
{{< hextra/hero-section >}}
  Selected Themes
{{< /hextra/hero-section >}}
</div>

- **Ground truth as a process:** complex AI evaluation requires evidence, adjudication, auditing, and revision.
- **Evaluation as instrumentation:** aggregate scores are often insufficient; we need diagnostics that reveal where and why systems fail.
- **Constraint-aware intelligence:** useful AI systems must allocate computation, communication, supervision, and verification under uncertainty.
- **Learning beyond labels:** models can exploit semantic, geometric, and structural information when direct supervision is limited.
- **Transformers as algorithmic systems:** trained models can sometimes be understood by extracting the procedures they implement.
