
Robust equipment pose estimation using synthetic data and machine learning
==========================================================================

# Abstract


We see this problem as a template matching problem: given a 3D model of equipment, detect it within 3D spatial data of an environment and estimate its pose. The challenge of template matching is that the actual sensor data of the object differs from the template. We expect this to be especially challenging due to occlusions, sensor error, and clutter in the environment. While the data is different, patterns will remain. We believe that deep learning networks are the best solution for identifying these patterns, particularly Siamese neural networks, just as they are for 2D template matching in images. We propose to adapt some very recent and impressive deep learning models from the related field of point cloud registration. We will be particularly focused on a Siamese neural network that performs 3D convolutions on a voxel representation of spatial data. While point cloud registration is concerned with aligning sets of point clouds for environment reconstruction, we believe approaches in this area will readily transfer to 3D template matching. We also propose to develop a virtual environment to simulate this problem. This will allow us to generate a very large amount of representative data, which will include occlusions, sensor error, and clutter. We will use this data to train neural networks, but even more importantly: test them. We believe that any approach to this problem needs to be tested against a large dataset in order to demonstrate feasibility.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2020|$140,000|slam, pose estimation, template matching, augmented reality, spatial data|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/JH/#2155)