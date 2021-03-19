
Distributed System for Privacy Protecting Speech Processing
===========================================================

# Abstract


This proposal explores feature representations for automatic speech processing algorithms with a focus on preserving the clients' privacy.  We address two different use cases of privacy:  a system that transcribes speech, but is unable to infer the identity of speakers, such as an anonymous tip hotline; and a system that identifies speakers, but is unable to recognize the communicated messages, useful in scenario where a many conversations may be under surveillance in order to locate and isolate a targeted individual. We investigate the feasibility of implementing such systems by focusing on the audio signal representations in a distributed system, where embedded devices compute representations and transmit them to a Big Data analytics service via the Internet.  Basic spectral acoustic features, tandem/bottleneck features, and high-dimensional outputs from deep neural networks will all be evaluated for both automatic speech recognition (ASR) and speaker identification (SID) tasks.  Performance will be assessed to identify configurations favorable for both use cases.  We additionally consider the possibility that an adversarial service operator may attempt to associate identities of speakers by clustering received requests, or reconstructing messages that have been transmitted over a mixture network.

In addition to serving the homeland security mission, the private-sector commercialization potential of this research is substantial.  It could prove useful to Remeeting, which is being developed as a mobile app and cloud service to record personal conversations; significant privacy concerns serve as barriers to adoption by individual and enterprise customers.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2015|$100,000|automatic speech recognition, speaker identification, anonymization, speaker normalization, embedded computing, big data analytics, internet of things|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/DJ/#1825)