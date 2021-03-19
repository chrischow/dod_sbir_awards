
Automating tilt and roll in ground-based photos and video frames
================================================================

# Abstract


NGA seeks an innovation to fully automate processes that recover camera orientation parameters, specifically for ground-based “photo” (aka image) and video frame use cases. The ability to use these ground-based systems represents an enhanced aspect to traditional photogrammetry, and in many regards, folding in hand-held systems, and considering the nuances associated with these collects, is yet another example of the continued steady convergence of photogrammetry with computer vision. That is particularly the case when we consider automating processing techniques and workflows. \n \nAutomation in that regard is the key. Currently, operators depend heavily on largely manual methods to recover orientation parameters and adjust for pitch. The time required, and conversely the error checking and workflow backtracking, places limiting constraints on workflow efficiency. \n \nThe specific automated workflow of interest would ingest images collected using a nominal modern hand-held system and use computer vision processing techniques to label the captured horizon. The module would thereafter automatically estimate pitch and roll – and do so within defined acceptance criteria. Subsequently upper and lower error bounds for the horizon would thereafter be automatically estimated. The expectation is that such a technique(s) could determine pitch and roll without the need for metadata.   \n \nGiven the points above our Phase I involves an approach that automates camera orientation parameter estimation, to include a demonstration of that proof-of-concept, suitable for NGA review and evaluation. \n \nOur technical objectives are as follows: (1) Develop techniques to identify the true horizon line from an image or video frame with the skyline (ridgeline) pre-defined; (2) Train any machine learning methods on gold-standard real and synthetic images, using standard methods for dividing test and train data; (3) Develop algorithms for estimating the roll and pitch parameters of the image attitude model from the identified true horizon line; (4) Identify methods for removing the effects of roll and pitch on the provided image; and (5) Validate all preliminary results based on known real and synthetic images with supplied metadata. \n \nWe believe these Phase I objectives align well with our proven expertise and breadth of ongoing, overlapping DoD initiatives. Specific details are provided in the technical proposal.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|National Geospatial-Intelligence Agency|2020|$99,965|ground-based, camera orientation, photogrammetry, computer vision, automation, workflow, true horizon line, pitch and roll|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards#2267)