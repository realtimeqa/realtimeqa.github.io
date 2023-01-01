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
|GPT-3 + Google Custom Search|2022-12-31 03:00:00|100.0|80.0|
|GPT-3 (Closed-Book)|2022-12-31 03:00:00|75.0|55.0|
|GPT-3 + DPR|2022-12-31 03:00:00|70.0|65.0|
|RAG + Google Custom Search|2022-12-31 03:00:00|70.0|45.0|
|T5 (Closed-Book)|2022-12-31 03:00:00|35.0|25.0|
|RAG + DPR|2022-12-31 03:00:00|15.0|15.0|



### Generation Track

| Model        | Submission Time (GMT) | EM | F1 | 
|:-------------|:---------|:---------|:-----|
|GPT-3 + Google Custom Search|2022-12-31 03:00:00|55.0|63.6|
|RAG + Google Custom Search|2022-12-31 03:00:00|35.0|45.9|
|GPT-3 + DPR|2022-12-31 03:00:00|15.0|21.9|
|GPT-3 (Closed-Book)|2022-12-31 03:00:00|10.0|19.5|
|T5 (Closed-Book)|2022-12-31 03:00:00|10.0|18.9|
|RAG + DPR|2022-12-31 03:00:00|0.0|3.1|



([see previous results](https://realtimeqa.github.io/docs/results/2022/))

## Make a new submission

1. Download the latest set of RealTime QA ([link](https://github.com/realtimeqa/realtimeqa_public))

1. Submit your model predictions. ([submission form](https://forms.gle/6xANYtedAf8UrqyY8))

    Submission examples (`.jsonl file`) are available [here](https://github.com/realtimeqa/realtimeqa_public/tree/main/baseline_results)
