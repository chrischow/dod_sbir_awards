
High Efficiency Acoustic Data Compressor
========================================

# Abstract


We propose a modular approach to compressing multi-channel acoustic time domain data. Our approach applies advanced multi-resolution denoising and outlier removal methods, for each channel, followed by an up-to-lag similarity cross-correlation and dynamic time warping based comparison step between the recovered waveforms, which would potentially decrease the amount of retained waveforms compared to the number of channels, replacing many by associated time lag and differencing information with respect to a set of pillars. Following this, a suitable transformation will be applied to each retained time domain waveform (to make the data amenable to lossless compression) and Burrows-Wheeler type compression, together with Arithmetic coding as the entropy encoder would be employed to achieve desirable compression ratio over the whole data set. This will be an improvement on the standard bzip2 like compressor (typically ranked as one of the best all-around lossless compression tools), which by default uses Huffman coding as the entropy encoder. A suitable decoding implementation will be built to deconstruct the waveforms for each channel. More advanced denoising methods utilizing machine learning will be experimented with. Our preliminary implementation indicates that 10x near lossless compression ratio is attainable.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2018|$125,000|dynamic time warping, burrows-wheeler compression, cross-correlation, arithmetic coding, outlier removal, multi-resolution denoising|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards#1977)