# Causal Effect of Wearing Glasses on Math Performance in Myopic Students

This repository contains the code and analysis for a study investigating the causal effect of wearing glasses on math test performance among myopic students in rural China. This project was conducted as part of the *Introduction to Causal Inference* course at the Data and Decision Sciences Faculty, Technion, taught by Prof. Uri Shalit during the Spring 2022 semester.
## Background

Vision problems can affect academic performance, yet misconceptions in rural China often discourage children from wearing glasses. This study uses data from a randomized controlled trial to estimate the causal effect of glasses-wearing on math achievements using various causal inference techniques.

## Contents
	•	data/: Data used in the analysis.
	•	analysis/: Jupyter Notebook used for causal inference methods.
	•	reports/: Final report and visualizations.

## Key Findings
- Average Treatment Effect (ATE) of wearing glasses on math scores: ~0.187
- Significant overlap in propensity scores between treatment and control groups.
- Estimations validated using multiple methods (S-learner, T-learner, matching, IPW, and causal graphs).

## Data Source

The data used in this project is adapted from the following study:

**“Effect of providing free glasses on children’s educational outcomes in China: cluster randomized controlled trial”**
BMJ 2014; 349 doi: https://doi.org/10.1136/bmj.g5740 (Published 23 September 2014)
Cite as: BMJ 2014;349:g5740

**Authors:**
Xiaochen Ma, Zhongqiang Zhou, Hongmei Yi, Xiaopeng Pang, Yaojiang Shi, Qianyun Chen, Mirjam E Meltzer, Saskia le Cessie, Mingguang He, Scott Rozelle, Yizhi Liu, Nathan Congdon

This randomized controlled trial assessed the effect of providing free glasses on academic performance in rural Chinese children with myopia.

**Trial Registration:** Current Controlled Trials ISRCTN03252665

Please refer to the original publication for detailed methodology and findings.

## Prerequisites
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, DoWhy, matplotlib
