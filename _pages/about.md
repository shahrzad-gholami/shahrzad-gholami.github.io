---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<head>
  <link rel="stylesheet" href="/assets/css/custom.css">
</head>

I am a Senior Research Scientist at the AI for Good Research Lab within Microsoft where I am dedicated to leveraging the transformative capabilities of artificial intelligence to address pressing global societal and environmental challenges. My research spans a diverse spectrum of applications, encompassing innovations in healthcare, environmental sustainability, and humanitarian initiatives. Before embarking on my journey at Microsoft, I earned my Ph.D. in Computer Science from the University of Southern California. Through my research and contributions, I am committed to driving positive change and shaping a better future for our world through the power of AI.

## Publications and Preprints

<div class="paper-image-text-pair">
<img class="paper-image" src="/images/mactel-short-paper" alt="damage-assessment">
<div class="paper-text">
  <b>Interpretable Ensemble-based Deep Learning Approach for Automated Detection of Macular Telangiectasia Type 2 by Optical Coherence Tomography</b>
  <br>
  <i>Shahrzad Gholami, Lea Scheppke, Rahul Dodhia, Juan M. Lavista Ferres , Aaron Lee</i>
  <br>
  ICML 2023 [<a href="https://openreview.net/pdf?id=amUYiXO9u0">paper</a>]
  <br><br>
  <div class="paper-short-summary">
	  <details>
		  <summary>TLDR: Developing ensemble deep learning model to detect Macular Telangiectasia Type 2 in OCT scans with interpretability using ResNet models and AdaBoost on a large dataset.</summary> 
		  We present an ensemble-based approach using deep learning models for the accurate and interpretable detection of Macular Telangiectasia Type 2 (MacTel) from a large dataset of Optical Coherence Tomography (OCT) scans. Leveraging data from the MacTel Project by the Lowy Medical Research Institute and the University of Washington, our dataset consists of 5200 OCT scans from 780 MacTel patients and 1820 non-MacTel patients. Employing ResNet18 and ResNet50 architectures as supervised learning models along with the AdaBoost algorithm, we predict the presence of MacTel in patients and reflect on interpretability based on the Grad-CAM technique to identify critical regions in OCT images influencing the models’ predictions. We propose building weak learners for the AdaBoost ensemble by not only varying the architecture but also varying amounts of labeled data available for training neural networks to improve the accuracy and interpretability. Our study contributes to interpretable machine learning in healthcare, showcasing the efficacy of ensemble techniques for accurate and interpretable detection of rare retinal diseases like MacTel.
	  </details>
  </div>
</div>
</div>
<br>


<div class="paper-image-text-pair">
<img class="paper-image" src="/images/building_damage-model_architecture.drawio (1).png" alt="damage-assessment">
<div class="paper-text">
  <b>On the Deployment of Post-Disaster Building Damage Assessment Tools using Satellite Imagery: A Deep Learning Approach</b>
  <br>
  <i>Shahrzad Gholami, Caleb Robinson, Anthony Ortiz, Siyu Yang, Jacopo Margutti, Cameron Birge, Rahul Dodhia, Juan M. Lavista Ferres</i>
  <br>
  ICDM 2022 [<a href="https://ieeexplore.ieee.org/document/10031100/">paper</a>][<a href="https://github.com/microsoft/building-damage-assessment-cnn-siamese">code</a>]
  <br><br>
  <div class="paper-short-summary">
	  <details>
		  <summary>TLDR: AI aids disaster response with a fast, accurate model using satellite imagery to assess post-disaster building damage levels, benefiting humanitarian efforts.</summary> 
		  Natural disasters frequency is growing globally. Every year 350 million people are affected and billions of dollars of damage is incurred. Providing timely and appropriate humanitarian interventions like shelters, medical aid, and food to affected communities are challenging problems. AI frameworks can help support existing efforts in solving these problems in various ways. In this study, we propose using high-resolution satellite imagery from before and after disasters to develop a convolutional neural network model for localizing buildings and scoring their damage level. We categorize damage to buildings into four levels, spanning from not damaged to destroyed, based on the xView2 dataset's scale. Due to the emergency nature of disaster response efforts, the value of automating damage assessment lies primarily in the inference speed, rather than accuracy. We show that our proposed solution works three times faster than the fastest xView2 challenge winning solution and over 50 times faster than the slowest first place solution, which indicates a significant improvement from an operational viewpoint. Our proposed model achieves a pixel-wise Fl score of 0.74 for the building localization and a pixel-wise harmonic Fl score of 0.6 for damage classification and uses a simpler architecture compared to other studies. Additionally, we develop a web-based visualizer that can display the before and after imagery along with the model's building damage predictions on a custom map. This study has been collaboratively conducted to empower a humanitarian organization as the stakeholder, that plans to deploy and assess the model along with the visualizer for their disaster response efforts in the field.
	  </details>
  </div>
</div>
</div>
<br>


<div class="paper-image-text-pair">
<img class="paper-image" src="/images/food-security-ML-workflow.png" alt="damage-assessment">
<div class="paper-text">
  <b>Food Security Analysis and Forecasting: A Machine Learning Case Study in Southern Malawi</b>
  <br>
  <i>Shahrzad Gholami, Erwin Knippenberg, James Campbell, Daniel Andriantsimba, Anusheel Kamle, Pavitraa Parthasarathy, Ria Sankar, Cameron Birge, Juan M. Lavista Ferres</i>
  <br>
  Data & Policy 2022, Vol 4 [<a href="https://www.cambridge.org/core/journals/data-and-policy/article/food-security-analysis-and-forecasting-a-machine-learning-case-study-in-southern-malawi/CA4DFA39526F318373259921C10D1C3F">paper</a>][<a href="https://medium.com/data-policy/forecasting-food-insecurity-levels-in-near-real-time-using-a-machine-learning-framework-24b553f70aca">blog</a>]
  <br><br>
  <div class="paper-short-summary">
	  <details>
		  <summary>TLDR: Using machine learning and high-frequency data, accurate food insecurity forecasts support humanitarian efforts in vulnerable communities, enhancing assistance delivery.</summary> 
		  Chronic food insecurity remains a challenge globally, exacerbated by climate change-driven shocks such as droughts and floods. Forecasting food insecurity levels and targeting vulnerable households is a priority for humanitarian programming to ensure timely delivery of assistance. In this study, we propose to harness a machine learning approach trained on high-frequency household survey data to infer the predictors of food insecurity and forecast household level outcomes in near real-time. Our empirical analyses leverage the Measurement Indicators for Resilience Analysis (MIRA) data collection protocol implemented by Catholic Relief Services (CRS) in southern Malawi, a series of sentinel sites collecting household data monthly. When focusing on predictors of community-level vulnerability, we show that a random forest model outperforms other algorithms and that location and self-reported welfare are the best predictors of food insecurity. We also show performance results across several neural networks and classical models for various data modeling scenarios to forecast food security. We pose that problem as binary classification via dichotomization of the food security score based on two different thresholds, which results in two different positive class to negative class ratios. Our best performing model has an F1 of 81% and an accuracy of 83% in predicting food security outcomes when the outcome is dichotomized based on threshold 16 and predictor features consist of historical food security score along with 20 variables selected by artificial intelligence explainability frameworks. These results showcase the value of combining high-frequency sentinel site data with machine learning algorithms to predict future food insecurity outcomes.
	  </details>
  </div>
</div>
</div>
<br>


<div class="paper-image-text-pair">
<img class="paper-image" src="/images/blood_QOL_trajectory.png" alt="damage-assessment">
<div class="paper-text">
  <b>Novel data analytics identify predictors of quality-of-life trajectories in patients with AML or high-risk Myeloid Neoplasms</b>
  <br>
  <i>Jordan Gauthier, Bianca Furtuna, ,Jacopo Mangiavacchi, Shahrzad Gholami, Juan M. Lavista Ferres, Rahul Dodhia, Mohamed L. Sorror</i>
  <br>
  Blood 2022, Vol 4 [<a href="https://ashpublications.org/blood/article/140/Supplement%201/5254/491544/Novel-Data-Analytics-Identify-Predictors-of">paper</a>]
  <br><br>
  <div class="paper-short-summary">
	  <details>
		  <summary>TLDR: Utilizing AI for quality-of-life trajectory prediction by employing non-supervised clustering and ordinal logistic regression on 503 Acute myeloid leukemia patients data enrolled on an observational clinical trial.</summary> 
		  Acute myeloid leukemia (AML) remains fatal in most patients (pts) with a 5-year survival probability of approximately 30% (less than 10% in pts aged 65 or older). Beyond survival, quality of life (QOL) can be significantly impaired by both disease and treatment-related factors. There is an urgent need to both characterize and identify factors predictive of QOL trajectories. Leveraging prospective data from 503 pts enrolled on an observational clinical trial, we implemented a novel statistical approach using non-supervised longitudinal clustering and ordinal logistic regression. We successfully identified: i) distinct QOL trajectories, ii) baseline factors independently associated with QOL trajectories.
	  </details>
  </div>
</div>
</div>
<br>


<div class="paper-image-text-pair">
<img class="paper-image" src="/images/wildfire-image.png" alt="damage-assessment">
<div class="paper-text">
  <b>Where there’s Smoke, there’s Fire: Wildfire Risk Predictive Modeling via Historical Climate Data</b>
  <br>
  <i>Shahrzad Gholami, Narendran Kodandapani, Jane Wang, Juan M. Lavista Ferres</i>
  <br>
  IAAI 2021 [<a href="https://ojs.aaai.org/index.php/AAAI/article/view/17797">paper</a>]
  <br><br>
  <div class="paper-short-summary">
	  <details>
		  <summary>TLDR: Predicting the spatio-temporal likelihood of wildfires via historical burned area, climate and geospatial data from three vast landscapes in India.</summary> 
		  Wildfire is a growing global crisis with devastating consequences. Uncontrolled wildfires take away human lives, destroy millions of animals and trees, degrade the air quality, impact the biodiversity of the planet and cause substantial economic costs. It is incredibly challenging to predict the spatio-temporal likelihood of wildfires based on historical data, due to their stochastic nature. Crucially though, the accurate and reliable prediction of wildfires can help the stakeholders and decision-makers take timely, strategic and effective actions to prevent, detect and suppress the wildfires before they become unmanageable. Unfortunately, most previous studies developed predictive models that suffer from some shortcomings: (i) in the evaluation phase, they do not take the temporal aspects into account precisely and they assume the independent and identically distributed random variables; (ii) they do not evaluate their approaches comprehensively, thus it is not clear if their proposed predictions and selected models remain reliable across different locations and years for practical deployment; and (iii) for the supervised learning models, they use predictor features and fire observations from the same time step in the training phase, which makes the inference task infeasible for future fire prediction. In this paper, we revisit the wildfire predictive modeling, explore the inherent challenges from a practical perspective and evaluate our modeling approach comprehensively via historical burned area, climate and geospatial data from three vast landscapes in India.
	  </details>
  </div>
</div>
</div>
<br>

<hr style="margin: 1.5em">
