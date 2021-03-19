
Identifying and Characterizing Cognitive Sensor Systems in Tactical Environments
================================================================================

# Abstract


The proposed DEfeating Cognitive Sensors through Tactical Adversarial Machine Learning (DECTAM) system will intelligently probe adversary cognitive sensor systems, characterize how the adversary system responds to changing stimuli, and using that information to identify vulnerabilities in the adversary system. Our approach takes academic research into adversarial learning and transitions those concepts into a practical, operational capability using a combination of experience commercializing machine learning and deep EW domain expertise. Until recently, electronic warfare has successfully employed architectures based entirely on a priori knowledge and look-up based ES/EA strategies.  However, the operational environment today is a challenging mix of these legacy systems as well as software defined radios, cognitive jammers, and cognitive radars. These cognitive adversaries involve unique challenges in their sophistication and adaptability, but also present an opportunity. By analyzing their behavior and characterizing their response to changing stimuli, we may be able to identify their vulnerabilities. DECTAM employs a two-step process to understand an adversary cognitive system and its vulnerabilities, which is based on current best practices from adversarial machine learning research.  First, DECTAM tries to acquire an understanding of the computational model that underlies the adversary cognitive system by observing the adversary’s behaviors in response to its surrounding environment and using machine learning to acquire an “inferred model.” This is done through observation only at first and then by intelligently selecting actions that our side can take to probe the adversary and learn more about its behavior. Next, DECTAM uses complex analysis of the inferred model to develop methods for “tricking” the adversary system by identifying situations where adversary is likely to make mistakes. We introduce two important innovations that allow these methods to be applied to the real-world domain on EW. First, as DECTAM is selecting probing actions or identifying vulnerabilities, it takes into account the numerous constraints in this domain that are not present in many conventional adversarial machine learning problems. Specifically, probing actions are selected by maximizing for: 1) the information gained by being able to observe the adversary’s reaction; 2) the feasibility of taking this probing action given the current operational environment; and 3) minimizing the distance from our normal behavior so as to avoid detection by the adversary. Second, because we don’t know what type of model underlies the adversary system, DECTAM maintains a list of viable models of different types which are continually assessed to determine how well they “fit’ the adversary behavior. This allows DECTAM to explore multiple model types in parallel, and avoids the errors and inefficiencies that are encountered when attempting to infer the wrong model type.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2021|$140,000|radar, adversarial machine learning, cognitive sensor system, electronic warfare|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards#2194)