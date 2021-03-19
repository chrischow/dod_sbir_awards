
A computational approach to early sepsis detection
==================================================

# Abstract


Abstract
SignificanceIn this SBIR projectwe propose to improve the performance of InSighta machine learningbased sepsis screening systemin situations of limited training data from the target clinical siteThe proposed
work will make possible prospective clinical deployments to sites which are smaller or lack clinical data
repositoriesby significantly reducing the amount of training data necessary down to a few weeks of clinical
observationClassicallya machine learning based system like InSight requires complete retraining for each
new clinical settingin turn requiring a new and large collection of data from each target deployment siteWe
will circumvent this requirement via transfer learning techniqueswhich transfer knowledge acquired previously
in a source clinical setting to a newtarget settingResearch QuestionsWhich transfer learning methods and
paired classification algorithms are most suitable for use with InSightrequiring minimal target site training data
while maintaining strong performanceAre these methods and algorithms robust across the several common
sepsis spectrum definitionsPrior WorkWe have developed InSight using the MIMIC III retrospective data
seton which it attains an area under the receiver operating characteristic curveAUROCoffor sepsis
detectionandforhour early sepsis predictionWe have also conducted pilot transfer learningexperiments in a different clinical taskmortality forecastingin which transfer learning yields afold
reduction in the amount of target site training data required to achieve AUROCSpecific AimsAimto implement and assess side by side four diverse transfer learning methods for a retrospective clinical sepsis
prediction taskwhere the source data set is MIMIC III and the simulated clinical target is a data set drawn
from UCSFAimto determine which among the best methods from Aimalso provide robust performance
when applied to two additional sepsis spectrum gold standardsMethodsWe will prepare implementations of
transfer learning methods which use instance transferresidual learning and or feature augmentationkernel
length scale transferand feature transferWe will test these methods with applicable classifiers on subsets of
the UCSF setusing cross validation and quantifying discrimination performance in terms of AUROCThe best
method classifier pairs will require no more thanexamples of septic patients from the target set and attain
AUROC superiorities ofinandhour pre onset sepsis prediction detectionrelative to the best tested
alternative screening systemsAimThe top three pairs will then be tested for robustness to gold standard
choiceusing septic shockandhourand SIRS based sepsishourgold standardsin these testsat
least one pair must again attainmargin of superiority in AUROC versus the alternative screening systemsAimFuture DirectionsThe results of these experiments will enable InSight to be robustly deployed to
diverse clinical sitesyielding high performance without the need for extensive target site data acquisition Narrative
Clinical decision supportCDSsystems present critical information to medical professionals by examining
patient data and providing relevant informationMachine learning is a powerful method for creating CDS toolsbut accessing its full strength requires re training with retrospective data from each target clinical siteWe will
use transfer learning techniques to dramatically reduce the amount of target site training data required by
InSightour machine learning based CDS tool for sepsis predictionand empirically evaluate several such
methods on a patient data setusing three different sepsis related gold standards  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2018|$310,782||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/JH/#2484)