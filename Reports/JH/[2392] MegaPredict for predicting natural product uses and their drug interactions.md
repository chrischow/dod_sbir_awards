
MegaPredict for predicting natural product uses and their drug interactions
===========================================================================

# Abstract


Project Summary
The objective of ‘MegaPredict’ is to enable scientists to generate predictions for a natural product (or any
molecule) and identify targets for efficacy assessment as well as identify any potential liabilities. We are building
on our previous work which has compiled a comprehensive collection of datasets for structure-activity data for a
broad variety of disease targets and other properties, in a form ready for model building. All of these models
utilize the many sources of curated open data, including ChEMBL, ToxCast etc. We have developed a prototype
of MegaPredict that utilizes Bayesian algorithm and ECFP6 fingerprints to output a list of prioritized ‘targets’. We
realize that neither the algorithm or the descriptors may be optimal therefore we propose to address this as we
validate MegaPredict and develop a product over this proposal. Our team is suitably qualified to develop the
software needed and we will leverage our large collaborator network to assist us in validating the activity of
compounds.
We will initially create a script to take a natural product and score it against many thousands of machine
learning models then rank the outputs to propose efficacy targets. We will use over 12,000 ChEMBL
derived target-assay / bioactivity groups extracted from the ChEMBL v24 database, as well as EPA Tox21
measurements and other public datasets, using methodology that we have already partially developed. We can
repeat this process for over 200 published compounds and access the outputs versus what is known. We intend
to compare how the approach performs with synthetic drugs or drug-like compounds as well as natural products.
We will assess whether other machine learning algorithms and molecular descriptors can improve
predictions. As we generate machine learning models such as Linear Logistic Regression, AdaBoost Decision
Tree, Random Forest, Support Vector Machine and deep neural networks (DNN) of varying depth we will assess
the predictions for natural products and compare with the Bayesian approach. We will compare ECFP6 with
other 2D, 3D descriptors and physicochemical properties in order to identify the optimal combination for
generating predictions for natural products and compare how this differs for synthetic compounds.
We will validate our predictions for natural product efficacy assessment. We will work closely with multiple
academic groups to generate predictions for at least 20 natural products of interest against over 20 different
targets or diseases. Our goal will be to identify potential targets that were previously unknown and then generate
in vitro data inhouse or with academic collaborators.
Develop a prototype user interface for input of a structure, processing an input molecule and output of
prioritized targets and liabilities. We have developed multiple software prototypes (e. Assay Central, MegaTox,
etc.) previously and will ensure a user-friendly interface and develop new visualization methods and algorithms
for prioritizing potential predicted targets based on the outputs of thousands of machine learning models.
In Phase I, we will use the software internally with collaborators to rapidly prototype it. In Phase II we will develop
a commercial product, and greatly expand our validation by building a larger network of academic and industry
partners that would help to prioritize features of most relevance. Using the machine learning models which we
have for natural products is limited because ECFP6 fingerprints cannot distinguish between these very different
classes of molecules. But this provides us with an opportunity by going for a andquot;pharmacophoreandquot; style approach
(ideally without using 3D conformations directly). We will therefore focus on developing a ‘3D shape-based
fingerprint’ or developing a novel ‘2D fingerprint’ that captures the ‘3D shape’ for natural- and druglike molecules.
Currently, the public datasets in ChEMBL and PubChem etc. are made up of mostly druglike molecules, but if
we have fingerprints that can compare drug-like and natural product-like molecules then we can likely reliably
use our MegaPredict models for natural products as well. We can also attempt to rank natural products with our
ChEMBL models or we can look through catalogs of druglike compounds using models derived from natural
products. That would be an important innovation. Additionally, in Phase II it would be important to see if we could
find uses for natural products with any of the 7000 rare diseases. Developing software that predicts potential
natural product drug interactions with various targets could be useful to regulatory organizations as well as the
pharmaceutical industry and may broaden utility of being able to more effectively mix natural product and druglike
compounds in models will have a profound effect on the value of cheminformatics in this arena.Project Narrative
Natural products have long been a source of therapeutics for human healthcare. Yet, some of the challenges
with developing natural product treatments are identifying potential human disease related targets and avoiding
others that might lead to undesirable natural product-drug interactions. Now there is considerable data in the
public domain for millions of molecules with thousands of targets and ADME/T related properties that it is possible
to use a suite of machine learning models for prospective prediction and profiling of a molecule’s properties from
structure alone. We aim to build on our preliminary efforts to date to create a prototype for MegaPredict using
various machine learning models which will enable academic and industrial scientists to generate predictions for
a natural product or any molecule of interest and identify potential targets for efficacy and toxicity liability
assessment. We will experimentally validate these predictions in-house or through our network of collaborators.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|National Institutes of Health|2019|$224,548||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/JH/#2392)