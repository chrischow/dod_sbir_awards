
Extreme Scale Sparse Linear Algebra Library for Machine Learning and PDE Simulation
===================================================================================

# Abstract


Many DOE science applications are now beginning to use models based on machine learning to complement traditional models based on the numerical solution of partial differential equations. Sparse matrix kernels are important for both machine learning based models and simulation based models. However, the performance of sparse-matrix computations can be very sensitive to the sparsity structure of the non-zero elements. Fur- ther, the sparsity patterns encountered in machine learning applications can differ considerably from those seen in PDE simulations. Sparse-matrix kernels available in libraries such as Intel’s MKL and Nvidia’s cuSPARSE exhibit significant performance variability across matrices of different sparsity structure, and ultra-high performance research implementation require non-standard data structures. ES-SciLA Extreme Scale Linear Algebra for Science Applications) targets high performance and scalability on a range of high performance and exascale) compute architectures for diverse science applications i.e., Machine Learning and PDE solvers). The ES-SciLA library will be implemented and optimized for multiple compute architectures, e.g., clusters, multi-core processors, many-core processors/accelerators, and GPU accelerators. ES-SciLA will be sparsity adaptive library, using an adaptive tiled implementation to optimize performance across a range of application types, architectures, and matrix sparstiy patterns. Phase I will research and design optimized SpMM that supports a wide range of sparsity patterns. The Phase I effort will include an initial prototype of SpMM that targets GPUs and CPUs. The implementation will use a sparsity-adaptive tile based CSR implementation that leverages dynamically selected microkernels and matrix signatures to optimize for both CPUs and GPUs architectures. Science applications are increasingly relying on machine learning to supplement, guide, and interpret traditional science based applications e.g., numerical simulation based applications). Machine learning is able to reduce the computational resources required, improve the time to solution, and/or increase the scientific knowledge extracted from such simulations. Therefore, the adoption of machine learning will transform the capabilities of traditional science applications. In addition, scientific simulations and machine learning applications have wide spread commercial use cases.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2020|$200,000||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/CC/#805)