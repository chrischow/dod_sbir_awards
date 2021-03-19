
GMTI Radar Target Classification Using Spectral and Tracking Data
=================================================================

# Abstract


We will develop an initial prototype to generate GMTI tracks, cluster the tracks into groups, extract features, remove feature correlation and reduce feature space dimensionality, and classify tracks to discriminate dismounts from animals and clutter.This prototype software will process GMTI data and will form the basis for conducting parametric studies on selecting features, revisit rate, sensor resolution, and specifying operating conditions. Our approach provides: -Process STANAG 4607 GMTI data to generate individual GMTI tracks; -Develop a clustering algorithm to form groups of tracks; -In parallel, process I and Q data to generate range-Doppler maps based on individual detections used in tracks; -Develop and extract group features and individual track featuresbased on signal processing analysis of details on range-Doppler maps from individual detections and cumulative features from sequences of range-Doppler maps, and features based on track-level kinematic behavior; -Perform Principal Component Analysis to identify related/correlated featuresjointly from track features and signal processing featuresand reduce the dimensionality of the feature space, as well as identify the relevant features that provide the discrimination; -Develop a machine learning approach to perform group classification; and -Conduct a parametric study that varies selected features, track length, revisit rate, and sensor resolution.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Army|2017|$99,979|gmti, dismount discrimination, feature extraction, range-doppler map, track features|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/CC/#1006)