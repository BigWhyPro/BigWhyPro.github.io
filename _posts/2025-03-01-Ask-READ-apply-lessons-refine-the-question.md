---
layout: post
title:  "Ask the best in world; READ the resonse, apply the lessons, then refine the question"
date:   2025-03-01 4:30:00
categories: template
---


## Become AI Savvy -- Ask Many, Many More Questions

**STOP thinking that you need to invent** ***everything.*** Somwhere somebody else has come up with a better way or at least has some ideas that you could use -- HUMBLY ask the best in the world for what they are doing. In order to become AI savvy -- ask many, many more questions and improve the AI-ification of your question asking technique.

We can START by [asking Copilot a simple question](https://github.com/copilot/c/2d964445-ed50-4967-90f6-97b4458cde33) to look into what the world is doing on something like *the latest and greatest work [on GitHub] on* ***causal inference*** ... after we have delved into that answer, we will have a better idea of what questions to ask AND we will ask the question of a smaller, better subset of who the BEST are.

#### Latest Issues Related to Causal Inference

1. **[todo](https://github.com/lucidrains/native-sparse-attention-pytorch/issues/1)** by [lucidrains](https://github.com/lucidrains)
   - **Created:** 21 hours ago
   - **Updated:** 21 minutes ago
   - **Body:** 
     ```
     - [ ] make sure compress and fine block sizes can be different, deal with the importance score as explained in paper
     - [x] handle < block size sequence lengths, make sure it doesn't break
       - [x] handle any block size < num selected blocks
       - [x] handle no blocks
     - [ ] flex attention for starters
       - [x] add for sliding windows
       - [ ] fine attention
       - [ ] add the mask function for compressed attention assuming at some future date, attention logits can be extracted
     - [x] replace einx get at
     - [x] ~allow for ablating this extra block causal diagonal in fine attention~ nevermind, it is necessary for the first block
     - [x] make it possible to customize the MLP for compressing key / value
     - [ ] add attention pool as a type of compression module, even if they said "MLP"
     - [ ] figure out relative positions from query to each compressed key. perhaps use the midpoint of the set of keys
     - [x] gqa
     - [ ] inference pathways
     - [x] ~figure out whether they used some soft topk or gating with the importance scores~ just use one hot straight through on compress attention probs and gate the selected keys and values
     - [ ] triton kernels only if in experiments it comes close to full attention - feel like i have tried every hierarchical attention technique during the pandemic.
     ```

2. **[When running DEEPSEEK with Ollama, model crashes occur](https://github.com/ollama/ollama/issues/9248)** by [mjdp168](https://github.com/mjdp168)
   - **Created:** 2 hours ago
   - **Updated:** 1 hour ago
   - **Body:**
     ```
     ### What is the issue?

     During the execution of DEEPSEEK, the following error occurred:
     Error: An error was encountered while running the model: read tcp 127.0.0.1:55564->127.0.0.1:54784: wsarecv: An existing connection was forcibly closed by the remote host.
     Observing that memory usage dropped to 0, which indicates a model crash. Could you suggest possible solutions?
     Thank.

     ### Relevant log output

     ```shell
     time=2025-02-20T19:36:37.412+08:00 level=INFO source=logging.go:50 msg=\"ollama app started\"
     ...
     ```

3. **[REVIEW]: The Causal Testing Framework](https://github.com/openjournals/joss-reviews/issues/7739)** by [editorialbot](https://github.com/editorialbot)
   - **Created:** 21 days ago
   - **Updated:** 1 hour ago
   - **Body:**
     ```
     Submitting author: @jmafoster1 (Michael Foster)
     Repository: https://github.com/CITCOM-project/CausalTestingFramework
     ...
     ```

4. **[Latest 15 Papers - February 20, 2025](https://github.com/jiangnanhugo/DailyArXiv/issues/27)** by [github-actions[bot]](https://github.com/apps/github-actions)
   - **Created:** 2 hours ago
   - **Updated:** 2 hours ago
   - **Body:**
     ```
     **Please check the [Github](https://github.com/jiangnanhugo/DailyArXiv) page for a better reading experience and more papers.**

     ## Time Series
     | **Title** | **Date** | **Comment** |
     | --- | --- | --- |
     | **[Causal Temporal Regime Structure Learning](http://arxiv.org/abs/2311.01412v3)** | 2025-02-19 |  |
     ...
     ```

#### Latest Repositories Related to Causal Inference

1. **[coffee_causality](https://github.com/AashishPatil2001/coffee_causality)** by [AashishPatil2001](https://github.com/AashishPatil2001)
   - **Created:** 5 days ago
   - **Updated:** 11 minutes ago
   - **Description:** Data-driven analysis of coffee shop sales using correlation, regression, and causal inference. A Jupyter Book project exploring foot traffic, weather patterns, and business analytics.

2. **[BayesianCausalInferenceShiny](https://github.com/boracelebi/BayesianCausalInferenceShiny)** by [boracelebi](https://github.com/boracelebi)
   - **Created:** 5 hours ago
   - **Updated:** 16 minutes ago
   - **Description:** A Shiny app for visualization of Bayesian Causal Inference Model of Duration Judgements.

3. **[BayesReg-CausalInference](https://github.com/michael-franke/BayesReg-CausalInference)** by [michael-franke](https://github.com/michael-franke)
   - **Created:** 19 June 2024
   - **Updated:** 56 minutes ago
   - **Description:** Bayesian data analysis and causal inference using Python & PyMC.

4. **[bayesian-analysis](https://github.com/abdullahau/bayesian-analysis)** by [abdullahau](https://github.com/abdullahau)
   - **Created:** 25 days ago
   - **Updated:** 1 hour ago
   - **Description:** Bayesian data analysis and causal inference using Python & PyMC.

5. **[CausalInferenceProject](https://github.com/Dan551Mizrahi/CausalInferenceProject)** by [Dan551Mizrahi](https://github.com/Dan551Mizrahi)
   - **Created:** 02 October 2024
   - **Updated:** 2 hours ago
   - **Description:** A project where I will be leaving my current studies about Causal Inference. It is a fascinating field that might revolutionate the industry.

6. **[Causal-Inference](https://github.com/JoaquinMateosBarroso/Causal-Inference)** by [JoaquinMateosBarroso](https://github.com/JoaquinMateosBarroso)
   - **Created:** 14 April 2024
   - **Updated:** 2 hours ago
   - **Description:** A project where I will be leaving my current studies about Causal Inference. It is a fascinating field that might revolutionate the industry.

7. **[HypEx](https://github.com/sb-ai-lab/HypEx)** by [sb-ai-lab](https://github.com/sb-ai-lab)
   - **Created:** 01 November 2023
   - **Updated:** 5 hours ago
   - **Description:** Fast and customizable framework for automatic and quick Causal Inference in Python.

8. **[PHAIR_EHR](https://github.com/kirilklein/PHAIR_EHR)** by [kirilklein](https://github.com/kirilklein)
   - **Created:** 22 days ago
   - **Updated:** 7 hours ago
   - **Description:** A fork of the EHR corebehrt repo for causal inference.

9. **[graphVCI](https://github.com/yulun-rayn/graphVCI)** by [yulun-rayn](https://github.com/yulun-rayn)
   - **Created:** 30 September 2022
   - **Updated:** 9 hours ago
   - **Description:** This repository implements Graph Variational Causal Inference (graphVCI), a framework that integrates prior knowledge of relational information into variational causal inference for the prediction of perturbation effect on gene expressions at single-cell and marginal level.

10. **[variational-causal-inference](https://github.com/yulun-rayn/variational-causal-inference)** by [yulun-rayn](https://github.com/yulun-rayn)
    - **Created:** 04 June 2022
    - **Updated:** 9 hours ago
    - **Description:** This repository implements Variational Causal Inference (VCI), a variational Bayesian causal inference framework for high-dimensional counterfactual and robust interventional inference.

### Note
- The results provided above are [of course] necessarily incomplete. There are a total of 6341 issues and 3396 repositories related to causal inference.
- For more detailed information and to explore further, please visit the following links:
  - [Issues related to causal inference](https://github.com/search?q=is%3Aissue+causal+inference&sort=updated&order=desc)
  - [Repositories related to causal inference](https://github.com/search?q=causal+inference&sort=updated&order=desc)