
Early Identification of Acute Kidney Injury Using Deep Recurrent Neural Nets, Presented with Probable Etiology
==============================================================================================================

# Abstract


Abstract
SignificanceIn this SBIR project we propose to develop Previsea novelsoftware based clinical decision
supportCDSsystem for predicting acute kidney injuryAKIand attributing AKI to one of several causal
mechanismsetiologiesPrevise will use machine learning methods and information drawn from the electronic
health recordEHRto identify the early signs of acute kidney injuryBy doing so before the clinical syndrome
of AKI is fully developedPrevise will give clinicians the time to intervene with the goals of preventing further
kidney damageand decreasing the sequelae of AKICombining this prediction module with a second module
that suggests the underlying causes responsible for an incipient or full AKIPrevise will enable clinicians to
make earlier and better informed treatment decisions for AKI patientsResearch QuestionCan a machinelearning based CDS predict the development and progression of AKI in hospitalized patientshours in
advance of KDIGO stageorwith performance providing an area under the receiver operating
characteristic curveAUROCof at leastIs it possible to use a Bayesian model to infer the cause of AKI
with high accuracyAUROCPrior workWe have developed a prototype version of the Previse
system which predicts AKI up tohours in advance of KDIGO stageorcriteriawith an AUROC nearWe have previously developed machine learning based predictive tools for sepsisin hospital mortalityand other adverse patient events with performance significantly improved over commonly used rules based
scoring systemsSpecific AimsTo predict the onset of chart abstracted KDIGO stageorAKI in
retrospective datahours in advanceAimto use data drawn from the EHR to identify the cause of AKI
at time of onset with high accuracyand to present this causal inferenceits likelihoodand relevant evidence
supporting it in a human interpretable fashionAimMethodsWe will predict the onset of AKI using a
deeprecurrent neural networkRNNThis expressivenonlinear classifier will incorporate time series
information in the qualitative portions of the EHR and will also incorporate features derived from text
componentssuch as radiology reportsLabeling AUROC ofor higher athours pre KDIGO AKI will
constitute success in AimIn Aimwe will train a dynamic Bayesian network to identify the cause of AKIWe will train this system using semi supervised methodswhere the causes of a set of AKI examples will be
hand annotated by clinician expertsthese examples will be split into two groupswith some used for training
and the remainder for testingAimwill be successful if this training results in etiology identification accuracy
of at leastin the test setFuture DirectionsFollowing the proposed workthe combined Previse system
will be deployed for prospective studies at partner hospitals Narrative
Acute kidney injuryAKIaffects approximatelyof all hospitalized patients each year in the United Statescausing short term and lasting harmincluding increased risk of mortalityHoweverthe existing tools for acute
kidney injury detection have failed to offer significant anticipation of full blown AKIor to provide the insight into
the AKI s root causewhich are needed to make an impact on patient outcomesWe will develop Previsea
machine learning based prediction system that continuously monitors for incipient AKI and offers clinicians
probable root causes of AKI  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2018|$349,320||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/JH/#2367)