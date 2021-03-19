
Real-Time Virtual Assessment of MitraClip Placement
===================================================

# Abstract


ABSTRACT Mitral regurgitationMRis the most common type of valvular heart disease in patients over the age ofyears in the USDespite the prevalence of MR in the elderly populationhoweveralmost half of patients identified with moderatesevere MR are turned down for traditional open heart surgery due to co morbiditiesMitraClipMCis a recent percutaneous approach to treat MR by placement of MC in the center of the mitral valveMVto reduce MRDespite the positive short term outcomes of the MC procedure in reducing MRthe long term outcome can be further improved if the effects of MC on both the fluid and solid mechanics of the MV and left ventricleLVwere available at the time the clip is placedRecentlywe developed a physics based human cardiac function simulator for the optimal design of a novel annuloplasty ring with a sub MV element for correction of MRas well as physics based simulations of MC placementThe problem with these simulationsas far as clinical applications is concernedis they are extremely time consumingdays to complete simulations onprocessor clusterOne way to make these time consuming simulations clinically applicable is to run them in advance for a wide range of patient characteristicse gdegree of MRsize and shape of the MV and LVetcand MC placementsCurrentlywhen clinicians are ready to place the MC on the MVthey have at their fingertips real time data on degree of MRand size and shape of the MV and LV measured usingD transesophageal echocardiographyRT D TEEWe propose the development and validation of a searchable virtual patient atlasSVPAthat will provide the clinician with detailed predictions of patient outcomes in real time that are based on MC placement and the RT D TEE patient specific dataThe firstmodels in our SVPA will be created from existing RT D TEE datasets provided by National Heart Centre SingaporeNHCSThenwe will use our novel shape dictionary learning models to automatically generateadditional models for our SVPAMachine learning models will be trained with the simulation data in order to create machine learning FEML FEsurrogates that can predict FE outputs directly from the model geometryThis would enable real time prediction of patient specific MC device outcomesOur preliminary studies usingD heart simulations clearly show that the main advantage with the ML model over theD FE model is speedi eML runs inCPU second versusD FE model runs inCPU hours!We will validate the outcome predictions of our SVPA using an additionalexisting RT D TEE datasets with known MC patient outcomes provided by NHCSAfter the outcome prediction using SVPA for each casewe will use the dataset and the measured outcome to train the original SVPA further and validate a new dataset with the original and the updated SVPAWe will select the more accurate SVPAthe original or the updatedto determine possible correlations between the primary geometrical parameters and other patient overall biometric information with the MR and optimal MC placement NARRATIVE A leaky inlet valve of the major pumping chamber of the heart is the most common valvular heart disease in elderly patientsRecentlythe US Food and Drug Administration approved a device that can be inserted into the patient s heart using a catheterThe purpose of this Phase I proposal is to develop and validate a software tool for predicting patient specific outcomes in order to optimize this therapy for patients  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|National Institutes of Health|2019|$289,679||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards#2451)