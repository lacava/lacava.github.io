---
layout: page
title: Interpreting ML models from electronic health records
date:  2019-12-01 15:00:00 -0500
categories: interpetation
---

![Feature importances clustered with diagnosis.](/files/RF_feature_permutation_clustermap_cutoff_1.jpg){: .center}
*Feature importances clustered with diagnosis.*
{: .center}

Last month, I had the pleasure of attending AMIA 2019 Symposium to present some recent biomedical informatics work. 
You can see my slides [here](https://drive.google.com/file/d/0B1iHrZwOcNdaLUNrdkJ6bEZlZm9xUXdOaTZ1clFtaEZlZHZv/view?usp=sharing). 
This is the first work supported by my K99, the goal of which is to develop interpretable ML methods using electronic health records (EHR).

Many hospitals and biomedical informaticists are hoping that ML can build useful predictive models of patient outcomes.
Predictive models are already used to assist at point of care, for example via early warning systems and patient prioritization models. 
In this paper, we empirically analyzed the interpretability of models trained on EHR data. 
We found that, even when models perform similarly in prediction, they often disagree about which factors drive diagnoses. 
This effect was alleviated somewhat by replacing the use of 'built-in' measures of importance with permutation testing. 

You can read the [preprint on arxiv](https://arxiv.org/abs/1903.12074), or browse the [code on github](https://github.com/EpistasisLab/interpret_ehr).

