---
layout: page
permalink: /acceptedpapers/
title: Accepted papers
description: 
nav: true
---


### Research, metrics, and dataset papers

- **AlgebraNation Dataset: Educational Big Data to Support Fair Educational Machine Learning. Wanli Xing, Chenglu Li, and Walter Leite.**

	One of the major challenges for studies on promoting algorithmic fairness in educational machine learning can be the limited access to demographic information due to privacy and regulations. We presented a demographics-enriched dataset called AlgebraNation, with state end-of-course exam results, 893,190 assessment items, and 20,297,075 log entries by 12,697 Algebra I learners between 2017 and 2019. We discussed the data context, collection, and attributes of AlgebraNation, providing researchers with opportunities to adopt the dataset to investigate and implement fair EML toward building trustworthy and sustainable AI in education.
  
	[View full paper here.](/assets/pdf/FATED-2022_paper_Xing_AlgebraNation_Dataset.pdf)


- **Fair Classification via Transformer Neural Networks: Case Study of an Educational Domain. Modar Sulaiman and Kallol Roy.**

	Educational technologies nowadays increasingly use data and Machine Learning (ML) models. This gives the students, instructors, and administrators support and insights for the optimum policy. However, it is well acknowledged that ML models are subject to bias, which raises concerns about the fairness, bias, and discrimination of using these automated ML algorithms in education and its unintended and unforeseen negative consequences. The contribution of bias during the decision-making comes from datasets used for training ML models and the model architecture. This paper presents a preliminary investigation of the fairness of transformer neural networks on the two tabular datasets: Law School and Student-Mathematics. In contrast to classical ML models, the transformer-based models transform these tabular datasets into a richer representation while solving the classification task. We use different fairness metrics for evaluation and check the trade-off between fairness and accuracy of the transformer-based models over the tabular datasets. Empirically, our approach shows impressive results regarding the trade-off between fairness and performance on the Law School dataset.
	
	[View full paper here.](/assets/pdf/FATED-2022_paper_Sulaiman_Transformers.pdf)


- **Towards Equalised Odds as Fairness Metric in Academic Performance Prediction. Jannik Dunkelau and Manh Khoi Duong.**

	The literature for fairness-aware machine learning knows 
	a plethora of different fairness notions. It is however well- 
	known, that it is impossible to satisfy all of them, as certain 
	notions contradict each other. In this paper, we take a closer 
	look at academic performance prediction (APP) systems and 
	try to distil which fairness notions suit this task most. For 
	this, we scan recent literature proposing guidelines as to 
	which fairness notion to use and apply these guidelines onto 
	APP. Our findings suggest equalised odds as most suitable 
	notion for APP, based on APP’s WYSIWYG worldview as 
	well as potential long-term improvements for the population.
	
	[View full paper here.](/assets/pdf/FATED-2022_paper_Dunkelau_Equalised_Odds.pdf)

- **Who Gets the Benefit of the Doubt? Racial Bias in Machine Learning Algorithms Applied to Secondary School Math Education. Haewon Jeong, Michael D. Wu, Nilanjana Dasgupta, Muriel Médard and Flavio P. Calmon.**

  We present a large-scale study demonstrating how machine learning models trained on student data can perpetuate and---at worst---amplify racial discrimination and bias patterns that have existed in the American education system. We base our study on two datasets of middle and high school students collected in the United States. We find that standard machine learning models used to predict student math performance consistently give more benefit of the doubt to White and Asian students and are more pessimistic in their predictions to Black, Hispanic, and Native American students. Even more dangerously, these disparities are hidden by high accuracy numbers---the standard figure-of-merit used to evaluate machine learning performance. We also study the fairness implications of the racial composition of datasets used to train machine learning models that predict student performance. Our results show that changing the racial composition of the training dataset produces a surprising trade-off between false-positive and false-negative predictions between student groups. We discuss how we can leverage this effect as a tool for reducing racial gaps in prediction error patterns while preserving accuracy. We also benchmark several state-of-the-art fairness interventions on student data and report their performance. Our analyses provide guidelines for creating more racially just machine learning models in education.
	
	[View full paper here.](/assets/pdf/FATED-2022_paper_Jeong_Racial_Bias_ML_Algs.pdf)


### Encore papers

- **Algorithmic Bias in Education. Ryan Baker and Aaron Hawn.**
  
	In this paper, we review algorithmic bias in education, discussing the causes of that bias and reviewing the empirical literature on the specific ways that algorithmic bias is known to have manifested in education. While other recent work has reviewed mathematical definitions of fairness and expanded algorithmic approaches to reducing bias, our review focuses instead on solidifying the current understanding of the concrete impacts of algorithmic bias in education— which groups are known to be impacted and which stages and agents in the development and
  deployment of educational algorithms are implicated. We discuss theoretical and formal perspectives on algorithmic bias, connect those perspectives to the machine learning pipeline, and review metrics for assessing bias. Next, we review the evidence around algorithmic bias in education, beginning with the most heavily-studied categories of race/ethnicity, gender, and nationality, and moving to the available evidence of bias for less-studied categories, such as socioeconomic status, disability, and military-connected status. Acknowledging the gaps in what
  has been studied, we propose a framework for moving from unknown bias to known bias and from fairness to equity. We discuss obstacles to addressing these challenges and propose four areas of effort for mitigating and resolving the problems of algorithmic bias in AIED systems and other educational technology. 

  *Original citation:* Baker, R.S., Hawn, M.A. (in press) Algorithmic Bias in Education. To appear in *International Journal of Artificial Intelligence and Education*. 
	
	[View full paper here.](https://www.upenn.edu/learninganalytics/ryanbaker/AlgorithmicBiasInEducation_rsb3.7.pdf)

- **Building socially responsible conversational agents using big data to support online learning: A case with Algebra Nation. Chenglu Li, Wanli Xing, and Walter Leite.**

	A discussion forum is a valuable tool to support student learning in online contexts. However, interactions in online discussion forums are sparse, leading to other issues such as low engagement and dropping out. Recent educational studies have examined the affordances of conversational agents (CA) powered by artificial intelligence (AI) to automatically support student participation in discussion forums. However, few studies have paid attention to the safety of CAs. This study aimed to address the safety challenges of CAs constructed with educational big data to support learning. Specifically, we proposed a safety-aware CA model, benchmarked with two state-of-the-art (SOTA) models, to support high school student learning in an online algebra learning platform. We applied automatic text analysis to evaluate the safety and socio-emotional support levels of CA-generated and human-generated texts. A large dataset was used to train and evaluate the CA models, which consisted of all discussion post-reply pairs (n = 2,097,139) by 71,918 online math learners from 2015 to 2021. Results show that while SOTA models can generate supportive texts, their safety is compromised. Meanwhile, our proposed model can effectively enhance the safety of generated texts while providing comparable support.
  
	*Original citation:* Li, C., Xing, W., & Leite, W. (2022). Building socially responsible conversational agents using big data to support online learning: A case with Algebra Nation. *British Journal of Educational Technology*, 53(4), 776--803. https://doi.org/10.1111/bjet.13227
	
	[View full paper here.](https://bera-journals.onlinelibrary.wiley.com/doi/10.1111/bjet.13227)

- **Towards Equity and Algorithmic Fairness in Student Grade Prediction. Zach Pardos and Weijie Jiang.**
  Equity of educational outcome and fairness of AI with respect to race have been topics of increasing importance in education. In this work, we address both with empirical evaluations of grade prediction in higher education, an important task to improve curriculum design, plan interventions for academic support, and offer course guidance to students. With fairness as the aim, we trial several strategies for both label and instance balancing to attempt to minimize differences in algorithm performance with respect to race. We find that an adversarial learning approach, combined with grade label balancing, achieved by far the fairest results. With equity of educational outcome as the aim, we trial strategies for boosting predictive performance on historically underserved groups and find success in sampling those groups in inverse proportion to their historic outcomes. With AI-infused technology supports increasingly prevalent on campuses, our methodologies fill a need for frameworks to consider performance trade-offs with respect to sensitive student attributes and allow institutions to instrument their AI resources in ways that are attentive to equity and fairness.

  *Original citation:* Jiang, W. and Pardos, Z. A. (2021) Towards Equity and Algorithmic Fairness in Student Grade Prediction. *AIES '21: Proceedings of the 2021 AAAI/ACM Conference on AI, Ethics, and Society*. pp. 608-617.

  [View full paper here.](https://dl.acm.org/doi/abs/10.1145/3461702.3462623)


