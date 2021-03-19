
Using clinical treatment data in a machine learning approach for sepsis detection
=================================================================================

# Abstract


Abstract
SignificanceIn this SBIR projectwe propose to develop novel softwareHindSightthat will improve
InSighta machine learning based clinical decision supportCDSsystem for sepsis prediction and detectionHindSight will identify clinicianssepsis related decisions in the records of former patientsit will then use
these events to supply InSight with labeled examples of sepsis casesincorporating cliniciansjudgement to
demonstrate appropriate and inappropriate alarmsTogether with an online training module that accordingly
refines InSight s predictorsthis capability will enable InSight to quickly adapt to the idiosyncrasies of a
particular clinical deploymentreduce false or irrelevant alarmsand do both without explicit human
supervisionResearch QuestionCan a machine learning basedretrospective labeler learn to autonomously
label sepsis and sepsis treatments by integrating the total clinical recordthereby providing many high quality
examples and labels for training a sepsis CDSIn concert with an online learning algorithmcan this labeler
facilitate onlinesupervised learning without explicit human interventionPrior WorkWe have developed
InSight for application in a number of sepsis prediction settingsExisting InSight classifiers attain an area under
the receiver operating characteristic curveAUROCoffor sepsis detectionandforhour early
sepsis predictionSpecific AimsTo identify patients who were evaluated for sepsistreated for sepsisor
who actually had sepsis using the retrospective clinical patient record and label them accordinglyAimto
use these labels with an online learning algorithm to implement autonomoussupervised learning of alert
behavior which reflects clinician judgementAimMethodsWe will identify evaluatedtreatedand septic
patients using a machine learning labeler trained on retrospective data from patientselectronic health recordsEHRat time of dischargeUsing a set oftest casesseptichand annotated by our clinician
investigatorswe will assess the labeler s performanceLabeling AUROCwill constitute success in AimWe will develop an online learning algorithm which enables InSight to continuously retrain during
deploymentWith Aims labelerwe will simulate a deployment with online learningproducing a learning
curve of predictive AUROC on a held out test set versus number of observed patientsAimwill be
successful if the online training results in superior area under the learning curve versus the initial model and
periodic retrainingAll experiments will be executed using the MIMIC III data setFuture DirectionsFollowing the proposed workthe InSight system with an onlineHindSight based retraining module will be
deployed at partner hospitals for prospective studies Narrative
Clinical decision supportCDSsystems present critical information to medical professionals by examining
patient data and providing alertsMachine learning is a powerful method for creating CDS toolsbut it requires
labels which reflect the desired alert behaviorWe will develop software that examines discharged patientselectronic health recordsEHRidentifies clinicianssepsis treatment decisions and patient outcomesand
passes these labeled examples to an online algorithm for retraining InSightour machine learning based CDS
tool for real time sepsis prediction  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2018|$324,971||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/JH/#2485)