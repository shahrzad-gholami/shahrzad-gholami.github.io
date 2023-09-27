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

I am a Senior Applied Research Scientist in AI for Good Research Lab at Microsoft. I am passionate about harnessing the power of machine learning and artificial intelligence to tackle global societal and environmental challenges. My research spans a wide spectrum of applications, including environmental sustainability, humanitarian endeavors, and healthcare innovations. Before my tenure at Microsoft, I completed my Ph.D. in Computer Science at the University of Southern California. My line of research yielded promising results, culminating in the creation of PAWS (Protection Assistant for Wildlife Security) – an end-to-end AI solution that employs artificial intelligence techniques to forecast poachers’ behavior. This facilitates strategic patrols for the safeguarding of endangered wildlife worldwide. This effort garnered coverage from prominent media outlets like Forbes and BBC. My interests extend to diverse domains, including healthcare where I have made impactful contributions by employing advanced deep learning computer vision techniques for medical imaging data analysis, leading to enhanced disease detection. Additionally, my endeavors encompass predictive models for critical scenarios like wildfire and food security, integrating survey, climate, and geospatial data to drive insightful forecasts. I have also leveraged remotely sensed imagery data and deep learning computer vision techniques to develop disaster response models, aiding in rapid building damage assessment during crises.

## Publications and Preprints
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
		  <summary>TLDR: Developed post-disaster damage assessment deep learning models based on remote sensing data.</summary> 
		  Natural disasters frequency is growing globally. Every year 350 million people are affected and billions of dollars of damage is incurred. Providing timely and appropriate humanitarian interventions like shelters, medical aid, and food to affected communities are challenging problems. AI frameworks can help support existing efforts in solving these problems in various ways. In this study, we propose using high-resolution satellite imagery from before and after disasters to develop a convolutional neural network model for localizing buildings and scoring their damage level. We categorize damage to buildings into four levels, spanning from not damaged to destroyed, based on the xView2 dataset's scale. Due to the emergency nature of disaster response efforts, the value of automating damage assessment lies primarily in the inference speed, rather than accuracy. We show that our proposed solution works three times faster than the fastest xView2 challenge winning solution and over 50 times faster than the slowest first place solution, which indicates a significant improvement from an operational viewpoint. Our proposed model achieves a pixel-wise Fl score of 0.74 for the building localization and a pixel-wise harmonic Fl score of 0.6 for damage classification and uses a simpler architecture compared to other studies. Additionally, we develop a web-based visualizer that can display the before and after imagery along with the model's building damage predictions on a custom map. This study has been collaboratively conducted to empower a humanitarian organization as the stakeholder, that plans to deploy and assess the model along with the visualizer for their disaster response efforts in the field.
	  </details>
  </div>
</div>
</div>

<div class="paper-image-text-pair">
<img class="paper-image" src="/images/building_damage-model_architecture.drawio (1).png" alt="damage-assessment">
<div class="paper-text">
  <b>Food Security Analysis and Forecasting: A Machine Learning Case Study in Southern Malawi</b>
  <br>
  <i>Shahrzad Gholami , Erwin Knippenberg , James Campbell , Daniel Andriantsimba , Anusheel Kamle , Pavitraa Parthasarathy , Ria Sankar , Cameron Birge , Juan M. Lavista Ferres</i>
  <br>
  Data & Policy 2022 , Vol 4 [<a href="https://www.cambridge.org/core/journals/data-and-policy/article/food-security-analysis-and-forecasting-a-machine-learning-case-study-in-southern-malawi/CA4DFA39526F318373259921C10D1C3F">paper</a>][<a href="https://medium.com/data-policy/forecasting-food-insecurity-levels-in-near-real-time-using-a-machine-learning-framework-24b553f70aca">blog</a>]
  <br><br>
  <div class="paper-short-summary">
	  <details>
		  <summary>TLDR: Using machine learning and high-frequency data, accurate food insecurity forecasts support humanitarian efforts in vulnerable communities, enhancing assistance delivery.</summary> 
		  Chronic food insecurity remains a challenge globally, exacerbated by climate change-driven shocks such as droughts and floods. Forecasting food insecurity levels and targeting vulnerable households is a priority for humanitarian programming to ensure timely delivery of assistance. In this study, we propose to harness a machine learning approach trained on high-frequency household survey data to infer the predictors of food insecurity and forecast household level outcomes in near real-time. Our empirical analyses leverage the Measurement Indicators for Resilience Analysis (MIRA) data collection protocol implemented by Catholic Relief Services (CRS) in southern Malawi, a series of sentinel sites collecting household data monthly. When focusing on predictors of community-level vulnerability, we show that a random forest model outperforms other algorithms and that location and self-reported welfare are the best predictors of food insecurity. We also show performance results across several neural networks and classical models for various data modeling scenarios to forecast food security. We pose that problem as binary classification via dichotomization of the food security score based on two different thresholds, which results in two different positive class to negative class ratios. Our best performing model has an F1 of 81% and an accuracy of 83% in predicting food security outcomes when the outcome is dichotomized based on threshold 16 and predictor features consist of historical food security score along with 20 variables selected by artificial intelligence explainability frameworks. These results showcase the value of combining high-frequency sentinel site data with machine learning algorithms to predict future food insecurity outcomes.
	  </details>
  </div>
</div>
</div>
<hr style="margin: 1.5em">
