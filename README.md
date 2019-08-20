# ACE - Anti-forensic Contrast Enhancement
This repository has the code to the process of anti-forensically enhancing the contrast of an image as described in the paper "ACE - An Effective
Anti-forensic Contrast Enhancement Technique".


## Reference
```
@ARTICLE{7359180, 
author={H. {Ravi} and A. V. {Subramanyam} and S. {Emmanuel}}, 
journal={IEEE Signal Processing Letters}, 
title={ACE–An Effective Anti-forensic Contrast Enhancement Technique}, 
year={2016}, 
volume={23}, 
number={2}, 
pages={212-216}, 
doi={10.1109/LSP.2015.2509477}, 
ISSN={1070-9908}, 
month={Feb},}
```

## Instructions
```
normal_enhanced, antiforensic_enhanced = perform_CE(input_image, gamma) 
```
The main code is Perform_CE to which the input is an image and output is the
anti forensically contrast enhanced image. Look inside the codes for various
comments on what the input and outputs are and how to use them. 

The main function uses 'Anti_TV' that performs the 
actual TV norm based optimization as described in the paper



