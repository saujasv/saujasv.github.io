---
layout: single
title: Projects
permalink: /projects
---

## Program synthesis for linguistic rules
**SIGMORPHON Workshop @ ACL 2021**
**ICON 2021**

<img src="/assets/images/synthesis_thumbnail.png" width="100%">

Linguistics Olympiad problems are challenging reasoning problems that require a solver to 
infer linguistic rules that generalise from only a few given examples. We use program synthesis
to tackle this problem. We develop a domain-specific language for expressing linguistic rules,
and adapt a synthesis algorithm to synthesise rules for solving a set of phonology problems we curated.

[\[paper\]](https://aclanthology.org/2021.sigmorphon-1.7.pdf) [\[dataset\]](https://github.com/saujasv/phonological-generalizations)

## Pragmatic program synthesis
**NeurIPS 2021 Workshop on Meaning in Context: Pragmatic Communication in Humans and Machines**

<img src="/assets/images/pragmatics.png" width="100%">

When working with program synthesizers, humans pragmatically communicate their intent in their specification. However, synthesizers are designed to work on any specification, and don't leverage the fact that humans make the task easier. But, pragmatic inference as captured in theories of rational communication (RSA) is computationally expensive, and scales poorly to large program spaces. We break down the synthesis problem using approximating in such a way that it works well with pragmatic specification, and also allows for pragmatic inference at a much lower cost.

[\[paper\]](https://arxiv.org/abs/2204.02495) [\[code\]](https://github.com/saujasv/program_synthesis_pragmatics) [\[talk\]](https://slideslive.com/38970772/efficient-pragmatic-program-synthesis-with-informative-specifications)
