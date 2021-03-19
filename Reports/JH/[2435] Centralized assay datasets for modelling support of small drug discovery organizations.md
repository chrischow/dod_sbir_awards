
Centralized assay datasets for modelling support of small drug discovery organizations
======================================================================================

# Abstract


Summary
The objective of  Assay Central  is to compile a comprehensive collection of datasets for structure activity data
for a broad variety of disease targets and absorption  distribution  metabolism  excretion and toxicology
 ADMET  properties  in a form that is immediately ready for model building and other forms of analysis using
cheminformatics methods  This is aided by the existence of many sources of curated open data  and one in
particular  ChEMBL      will be used as the nucleus in Phase I  This bioassay data collection is incredibly
valuable  but not currently provided in a form that is ready to go for use by small research and development
 Randamp D  organisations that do not have their own in house cheminformatics teams  The effort required to
preprocess  filter  merge  validate and normalize the structure and activity data requires a great deal of
software expertise and medicinal chemistry domain knowledge  which are key skillsets that are rare and
expensive to combine within the same team 
Create a script to analyze the databases like ChEMBL  selected parts of PubChem and others      and
partition it into groups of compatible activity measurements against the same target  We will seed the
dataset collection with a set of      target assay groups that have been recently extracted from the ChEMBL
v   database  as well as EPA Tox   measurements    using methodology that we have already developed
 similar to that described in    
We will build error checking and correction software  We will apply best of breed methodology for
checking and correcting structure activity data   which errs on the side of caution for problems with non 
obvious solutions  so that we can manually identify problems and either apply patches  or datasource specific
automated corrections 
We will build and validate Bayesian models with the datasets collected and cleaned  For each of the
target activity groups  we will create a Bayesian model using ECFP  or FCFP  fingerprints  and this will be
one of the primary outputs from the project  Models will be evaluated using internal and external testing with
receiver operator characteristic  ROC andgt         the integral of the true negative rate   true positive rate curve
as well as the enrichment   Kappa value and positive predicted value  
We will develop new data visualization tools as a proof of concept in phase I  We have already begun to
explore preliminary visualization methods using multiple models  but these have so far focused primarily on a
handful of machine learning models selected from a very large list  New visualization techniques are required
to summarize large matrices of data  e g  a list of proposed structures vs  thousands of target models 
In Phase II we will expand by upgrading to newer ChEMBL releases  selectively incorporating screening runs
from other databases  such as PubChem     These tools will consist of software created explicitly for this
project  particularly web based interfaces   as well as enhanced functionality added to  rd party tools that we
influence  e g  mobile apps  and open source projects that we have already contributed to  e g  CDK for
fingerprints and Bayesian modelling   We will widely publicise Assay Central at conferences and in papers 
Being able to use transparent computational models simultaneously for visualizing activity trends for multiple
targets  both diseases and ADMET  removes the burden of curation or purchasing and maintaining expensive
software  and drastically simplifies the addition of new data  It also represents a new frontier of drug discovery
as a world of small  agile distributed Randamp D organizations has access to valuable public datasets that can inform
their research  Such computational models will assist in drug repurposing efforts internally and with our
collaborators while likely identifying new compounds for a wide array of drug discovery projects Narrative
There are massive publically accessible databases that include a broad variety of disease targets and
absorption  distribution  metabolism  excretion and toxicology  ADMET  properties that are not a form that is
immediately ready for machine learning model building  The  Assay Central  project will compile a
comprehensive collection of these datasets  from PubChem and ChEMBL  for structure activity data  This will
enable the user to quickly and automatically use machine learning models for various targets and properties 
The approach will also have high value for drug repurposing efforts and identifying new compounds for targets
with creation of new IP in our own research on neglected and rare diseases and in the laboratories of
customers  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|National Institutes of Health|2017|$149,999||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards#2435)