# vgail
CSE 291 Deep Reinforcement Learning Final Project
---
In this project, we used GAIL and Info-GAIL as baselines, implemented RiskSensitive-GAIL to study risk measurements in GAIL derivations, and finally proposed a new risk measurement optimization metric called Variance-GAIL. The goal of this project is to first investigate if adding a risk measure would help to improve model performance, and then to compare between the efficacy of tail-related and variance-related risk metrics.

This project is built upon the codebase by [Stanford Intelligent Systems Laboratory](https://github.com/sisl/hgail). We adopted GAIL and Info-GAIL models from the original codebase, and implemented [RS-GAIL](https://arxiv.org/abs/1808.04468) and V-GAIL upon this infrastructure.
