
Artificial neural networks for high performance fully automated particle tracking analysis even at low signal to noise regimes
==============================================================================================================================

# Abstract


Abstract  Particle tracking  PT  is a powerful biophysical tool for elucidating molecular interactions  transport
phenomena and rheological properties in complex biological environments  Unfortunately  PT remains a niche
tool in life and physical sciences with a limited user base  in large part due to significant time and technical
constraints in extracting accurate time variant positional data from recorded movies  These constraints are
exacerbated in experiments with low signal to noise ratios or substantial heterogeneity  as frequently
encountered with nanoparticles and pathogens in biological fluids  Currently available software that attempts
to automate the movie analysis process rely almost exclusively on assigning static image filters based on
specific intensity  pixel size and signal to noise ratio thresholds  Unfortunately  when applied to actual
experimental data with substantial spatial and temporal heterogeneity  the current software generally produces
substantial numbers of false positives  i e  tracking artifacts  or false negatives  i e  missing actual traces   and
frequently both  Frequent user intervention is thus required to ensure accurate tracking even when using
sophisticated tracking software  markedly reducing experimental throughput and resulting in substantial user 
to user variations in analyzed data  The time required for accurate particle tracking analysis makes PT
experiments exceedingly expensive compared to other commonly used experimental techniques in life
sciences  These same tracking analysis limitations have effectively precluded investigators from undertaking
more sophisticated  D PT  even though the microscopy capability to obtain such movies is readily available
and critical scientific insights can be gained from  D PT  To circumvent the challenges with currently available
particle tracking software  we have developed a new approach for particle identification and tracking  based on
machine learning and convolutional neural networks  CNN   CNN is a type of feed forward artificial neural
network designed to process information in a layered network of connections that mimics the organization of
real neural networks in the mammalian retina and visual cortex  Unlike most CNN imaging models that are
trained to make predictions on static images  we have trained our CNN to input adjacent frames so that each
prediction includes information from the past and future  thus effectively performing convolutions in both space
and time to infer particle locations  Similar principles of image analysis are now being harnessed by
developers of autonomous vehicle technologies to distinguish the motions of different objects on the road  We
have applied our CNN tracking algorithm to a wide range of  D movies capturing dynamic motions of
nanoparticles  viruses and highly motile bacteria  achieving at least    fold time savings with virtually no need
for human intervention while maintaining robust tracking performance  i e  low false positive and low false
negative rates   In this STTR proposal  we seek to focus on further optimization and testing of our neural
network tracking platform for  D PT  including the use of cloud computing  Aim     and extending our neural
network tracker to enable accurate  D PT  Aim     Our vision is to popularize PT as a research tool among
researchers by minimizing the time and labor costs associated with PT analysis Narrative
Particle tracking is a powerful biophysical tool in life and physical sciences  but unfortunately its application has
been strongly limited by inefficiencies in accurately extracting particle traces from raw movies  Unlike
conventional particle tracking methods  we have combined artificial intelligence and machine learning to create
a computational neural network that can recognize objects in much the same way as the human eye  and
which consistently provided superior and truly automated tracking performance compared to current
alternatives  This STTR will establish the feasibility of using our computational neural network for robust  D
and  D particle tracking analysis  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|National Institutes of Health|2017|$224,997||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/JH/#2328)