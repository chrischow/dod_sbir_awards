
Static Analysis of AI Systems
=============================

# Abstract


Toolkits for Artificial Intelligence (AI) are increasingly being used in government and industry.  If such systems have access to sensitive information, it is important to know their security properties.  A toolkit may contain low-level flaws, such as buffer-overrun errors that allow an attacker to gain control of the host system.  Or, there may be flaws in the rule base of a system implemented with the toolkit that allow unauthorized access to sensitive information.  We propose the detailed study of the security properties of CLIPS, a widely used expert-system shell in two parts.  The first part will be a detailed analysis of the source code of the system using static analysis tools and other methods to find low-level flaws.  The second part will be a study of the CLIPS language and the exploration of static and dynamic approaches to create secure CLIPS programs.   A promising approach is to model the CLIPS system as a weighted push down system, and to use model-checking techniques to implement a range of security analyses, including termination analysis and information flow.  The results will include a design for a tool to be prototyped in Phase II, and guidelines on how to write a secure CLIPS specification.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Defense Advanced Research Projects Agency|2004|$99,000||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards#129)