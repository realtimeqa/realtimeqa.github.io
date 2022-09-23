---
layout: default
title: Home
nav_order: 1
description: "RealTime QA project page"
permalink: /
---

# Welcome to RealTime QA
{: .fs-9 }


{: .fs-6 .fw-300 }

[Check the latest results](#latest-results){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Make a new submission](#make-a-new-submission){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

[Check out the GitHub](https://github.com/realtimeqa/realtimeqa_public){: .btn .btn-secondary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Check out the paper](https://arxiv.org/abs/2207.13332){: .btn .btn-secondary .fs-5 .mb-4 .mb-md-0 .mr-2 }

---

## Latest results 

### Multiple Choice Track

| Model        | Submission Time (GMT) | Original | NOTA | 
|:-------------|:---------|:---------|:-----|
|GPT-3 + Google Custom Search|2022-09-24 03:00:00|63.3|56.7|
|GPT-3 + DPR|2022-09-24 03:00:00|53.3|46.7|
|GPT-3 (Closed-Book)|2022-09-24 03:00:00|50.0|33.3|
|RAG + Google Custom Search|2022-09-24 03:00:00|46.7|36.7|
|T5 (Closed-Book)|2022-09-24 03:00:00|36.7|43.3|
|RAG + DPR|2022-09-24 03:00:00|23.3|23.3|



### Generation Track

| Model        | Submission Time (GMT) | EM | F1 | 
|:-------------|:---------|:---------|:-----|
|GPT-3 + Google Custom Search|2022-09-24 03:00:00|30.0|34.0|
|RAG + Google Custom Search|2022-09-24 03:00:00|20.0|24.4|
|GPT-3 + DPR|2022-09-24 03:00:00|10.0|13.7|
|GPT-3 (Closed-Book)|2022-09-24 03:00:00|6.7|15.7|
|T5 (Closed-Book)|2022-09-24 03:00:00|6.7|13.2|
|RAG + DPR|2022-09-24 03:00:00|0.0|0.0|



([see previous results](https://realtimeqa.github.io/docs/results/2022/))

## Make a new submission

1. Download the latest set of RealTime QA ([link](https://github.com/realtimeqa/realtimeqa_public))

1. Submit your model predictions. ([submission form](https://forms.gle/6xANYtedAf8UrqyY8))

    Submission examples (`.jsonl file`) are available [here](https://github.com/realtimeqa/realtimeqa_public/tree/main/baseline_results)
