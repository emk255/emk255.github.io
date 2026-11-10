---
layout: page
title: research
permalink: /projects/
description: LLM evaluation, scientific agents, and research software.
nav: true
nav_order: 3
---

## Graph representations for AI co-scientists
**Northeastern University · September 2026–present · Advisor: Tina Eliassi-Rad**

I study how the representation of scientific graphs shapes LLM agents' analysis. My current work compares representations of 172 gene co-expression networks, including large, dense graphs with up to 7.6 million edges. The goal is to understand how agents use graph structure and how representation choices affect their conclusions.

## Correlated errors in large language models
**Cornell University · June 2024–December 2025 · Advisor: Nikhil Garg**

Do different models provide independent perspectives? Our ICML 2025 paper studies shared errors across LLMs and their consequences for evaluation and hiring. I designed and implemented a cross-model evaluation; the hiring study covered 1,800 resume–job pairs and 20 LLMs, showing how correlated errors can systematically exclude the same applicants.

[Paper](https://proceedings.mlr.press/v267/kim25e.html) · [Code](https://github.com/nikhgarg/llm_correlated_errors_public/)

## Scientific reasoning and coding evaluation
**UIUC ScaleML Lab · August 2025–May 2026 · Advisor: Tong Zhang**

I investigated performance degradation when LLMs used built-in web search on a challenging multimodal physics benchmark. I also built benchmark components covering 217 geometry problems evaluated with AlphaGeometry's symbolic proof engine and 53 scientific-computing tasks that checked LLM-generated Fortran against reference outputs.

## pyKurucz and stellar spectrum synthesis
**Research software · November 2025–June 2026 · Collaborator: Yuan-Sen Ting**

As lead developer of pyKurucz, I used coding agents to translate legacy Kurucz ATLAS12 and SYNTHE Fortran codes into modular Python, validating the implementation against the original programs. The software enables stellar-spectrum experiments and integration with machine learning workflows, and served as the foundation for Payne Zero.

[pyKurucz paper](https://arxiv.org/abs/2603.11693) · [Code](https://github.com/tingyuansen/pykurucz) · [Payne Zero paper](https://arxiv.org/abs/2607.24141)

## Computational social science
**Cornell Nexus Scholars · May–July 2023 · Advisor: David Strang**

I built an automated pipeline using Selenium and ETL processes to collect 65,000 New York Times obituaries from LexisNexis into MongoDB, then integrated Google Trends data to analyze search interest.
