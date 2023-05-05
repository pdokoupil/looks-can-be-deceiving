# About

This repository contains supplementary material for a paper titled *Looks Can Be Deceiving: Linking User-Item Interactions and \\User's Propensity Towards Multi-Objective Recommendations*.

# Abstract
Multi-objective recommender systems (MORS) provide suggestions to users according to multiple (and possibly conflicting) goals.
When a system optimizes its results at the individual-user level, it tailors them on a user’s propensity towards the different objectives.
Hence, the capability to understand users’ fine-grained needs towards each goal is crucial. In this paper, we present the results of a user
study in which we monitored the way users interacted with recommended items, as well as their self-proclaimed propensities towards
relevance, novelty and diversity objectives. The study was divided into several sessions, where users evaluated recommendation lists
originating from a relevance-only single-objective baseline as well as MORS. We show that despite MORS-based recommendations
attracted less selections, its presence in the early sessions is crucial for users’ satisfaction in the later stages. Surprisingly, the selfproclaimed
willingness of users to interact with novel and diverse items is not always reflected in the recommendations they accept.
Post-study questionnaires provide insights on how to deal with this matter, suggesting that MORS-based results should be accompanied
by elements that allow users to understand the recommendations, so as to facilitate their acceptance.

# Repository Structure
Repository contains the following files:
- [ResultsGeneration.ipynb](./ResultsGeneration.ipynb) Jupyter Notebook used to generate results in the paper
- [AdditionalResultsGeneration.ipynb](./AdditionalResultsGeneration.ipynb) **TODO** Jupyter Notebook that can be used to generate additional results that did not make it to the paper
- [results](./results) directory with results from the paper
- [additional_results](./additional_results) **TODO** directory with additional results
- [data](./data) additional (input) data for the notebooks, can be downloaded from the [OSF.io repository](https://osf.io/7ekjp/?view_only=18f990bf547b4903b13ac3bc15544af1)