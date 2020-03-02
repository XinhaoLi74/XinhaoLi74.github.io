---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate in  [Fourches's lab](https://www.fourches-laboratory.com/) in the Department of Chemistry at North Carolina State University in Raleigh, NC, USA. I am interested in applying machine learning, especially deep learning, techniques for solving challenge problems in chemistry, drug discovery and environmental toxicology. 

My primary research interests involve:  
- Quantitative Structure-Activity Relationships (QSAR) modeling.
- Development of data-driven and interpretable molecular representations via deep learning.
- Molecular informatics approach for visualizing and navigating chemical space.

## Research Projects

1. Reliable *in silico* approaches to replace animal testing for the evaluation of potential acute toxic effects are highly demanded by regulatory agencies. The first research project of my Ph.D. was developing a hierarchical QSAR modeling method that integrates binary, multiclass and regression models for predicting three [acute oral systemic toxicity endpoints](https://ntp.niehs.nih.gov/whatwestudy/niceatm/test-method-evaluations/acute-systemic-tox/models/index.html?utm_source=direct&utm_medium=prod&utm_campaign=ntpgolinks&utm_term=tox-models) used by a variety of regulatory bodies for toxicity test. This method represents (1) a promising alternative prediction method to animal testing; (2) a more efficient and powerful ensemble method compared to the model consensus (predictions averaging). This project is a collaboration with [Dr. Nicole Kleinstreuer](https://www.niehs.nih.gov/research/atniehs/dntp/assoc/niceatm/staff/kleinstreuer/index.cfm) at the NIEHS and published on [_Chemical Research in Toxicology_](https://pubs.acs.org/doi/10.1021/acs.chemrestox.9b00259).

![HQSAR Modeling Workfolw](/images/HQSAR.png)

2. Quantitative Structure–Activity Relationships (QSAR) are statistical, data-driven models that establish quantitative links between an experimental activity (e.g., binding affinity, inhibition potency) and chemical structures. QSAR models are typically developed using supervised machine learning algorithms and further validated using a variety of statistical procedures and metrics. Good model performance usually requires a decent amount of labeled data, but collecting labels is expensive and hard to be scaled up. Thus, it would be highly relevant to utilize the tremendous unlabeled compounds from publicly-available datasets. Self-supervised learning opens up a huge opportunity for better utilizing unlabeled data. **Mol**ecular Prediction Model Fine-Tuning (**MolPMoFiT**) approach, an effective transfer learning method based on **self-supervised pre-training + task-specific fine-tuning** for QSAR modeling ([_ChemRxiv_ ](https://chemrxiv.org/articles/Inductive_Transfer_Learning_for_Molecular_Activity_Prediction_Next-Gen_QSAR_Models_with_MolPMoFiT/9978743)). 

![MolPMolFiT Overview](/images/MolPMolFiT.PNG)

