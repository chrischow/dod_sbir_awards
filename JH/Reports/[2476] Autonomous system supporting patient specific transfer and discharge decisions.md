
Autonomous system supporting patient specific transfer and discharge decisions
==============================================================================

# Abstract


Significance  In this SBIR project  we propose to improve the utility of AutoTriage  a machine learning based
clinical decision support  CDS  system  by integrating clinician intervention medical information into its
predictions  Despite identified needs for CDS systems in patient transfer and discharge decisions  existing
tools do not meet high standards for sensitivity and specificity  This is because current CDS methods are
unable to distinguish changes in patient health due to clinician intervention from those arising due to an internal
homeostatic mechanism  Thus  for example  existing tools may erroneously suggest discharge for a patient
currently undergoing a life sustaining treatment  Research Question  Can machine learning principles be
used to create a classifier which incorporates signs of clinical intervention to inform transfer and discharge
decision support  ultimately leading to higher quality predictions  In addition  will such a tool be able to
maintain its performance when tested on a different patient population or one for which the data quality is much
poorer  Prior Work  We have developed AutoTriage  a machine learning based CDSS for    hour mortality
prediction  On the publicly available MIMIC III retrospective data set  this system attains an area under the
receiver operating characteristic curve  AUROC  of       which is superior to commonly used triage scores
MEWS  AUROC          SOFA         and SAPS II        on the same data set  Specific Aims  To integrate
clinician intervention information into existing AutoTriage software  Aim     and to test the robustness of this
modified tool to changes in patient population and data quality  Aim     Methods  We will create gold
standards for periods of clinician intervention  using chart events and keywords from clinician notes  Then  we
will train a binary classifier for identifying these periods and  ultimately  use the classifier to modify AutoTriage
scores  Robustness studies will be performed on the retrospective UC ReX and sparse MIMIC III databases 
Successful completion of Aim  will be demonstrated if     of all hours of clinician intervention are correctly
classified  if the test set area under the ROC curve improves by    over its current value  and if    day
readmission predictions are     more accurate for patients treated within the last hour  Aim   will be
completed if AutoTriage ROC area performance is within        of its original value for both UC ReX and
sparse MIMIC III sets  Future Directions  Following the proposed work  the AutoTriage system will be
deployed at the sites of our ongoing clinical implementations  During this study  we project that AutoTriage will
assess mortality risk for        ICU patients per year  helping clinicians more effectively allocate interventions
totaling $   million Clinical decision support  CDS  systems aid medical professionals by presenting them with information needed to make better decisions about patient care  often in the form of alerts  To be of practical benefit  CDS tools must provide recommendations which accurately reflect the ongoing treatment provided by the clinician  We propose to incorporate knowledge of a clinician s actions  like the administration of fluids or of antibiotics  into a CDS tool in order to improve the assessment of a patient s ability to be discharged or transferred safely  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|National Institutes of Health|2017|$347,772||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/JH/#2476)