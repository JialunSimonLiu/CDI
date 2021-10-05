# Coherent Diffraction Imaging 
**The basic idea of the algorithm**:The two phase retrieval algorithms presented here are Error Reduction (ER) and Gerchberg–Saxton (GS) algorithms. Our investigation primarily focused on evaluating the performance of the Coherent diffraction imaging (CDI) experiment in Diamond Light Source's I-13 branchline using the ER algorithm.

![Alt Text](https://github.com/JialunSimonLiu/Coherent-Diffraction-Imaging/blob/main/pictures/Error%20reduction%20algorithm.png)

1.The model used an iterative feedback algorithm known as the oversampling algorithm to reconstruct the image off a generated intensity distribution.

2.The chi-square between the generated images and the original sample image was measured to determine the similarities per iteration.

3.A Comparison was made between both Diamond 1, Diamond 2 and an ideal coherent beam. (see files: Results of Diamond I.ipynb, Results of Diamond II.ipynb, Phase_retrieval_algorithm(coherent_lights).ipynb)

**General physical background**:
CDI is a lensless tomographic technique that measures the diffraction pattern of x-rays that have scattered off of a nanoscaled sample (e.g.nanotube). From this diffraction pattern it is possible to reconstruct a highly resolved image of the sample and thus is a widely used technique in both material and biomedical sciences. **Why do we need the ER algorithm:** In CDI the resolution of the image is dependent solely on the coherence of the incoming x-ray beam. However, a major drawback with CDI is that by measuring the scattered intensity distribution all phase information of the x-ray beam is lost. Thus information of the sample is also lost and must be iterated over to retrieve an image of the sample.

![Alt Text](https://github.com/JialunSimonLiu/Coherent-Diffraction-Imaging/blob/main/pictures/Coherant%20diffraction.png)

**Results**:
The results show an increase in the resolution with each iteration. From our computational model, Diamond II does not improve the quality of the diffraction pattern. It was also found that the ideal case had no effect in the resolution of the diffraction pattern.

There are three potential causes for such a phenomenon to occur: • The chi-square limit • Computational precision of the results reaching a value that is indistinguishable • Our simplified model does not account for how the upgrade affects the efficiency of the upgrade.

**Conclusions**:
This upgrade also results in :
• higher flux - more photons per area per second
• smaller beam - less overall radiation damage
• shorter pulses - improved time resolution

Diamond II opens up the following research areas:
• Battery research
• G protein-coupled receptors
• Target-drug kinetics
• Study of Coronaviruses in a more efficient way

From our findings we believe that, in an age of exponential technological development, it is evident that institutions, such as the Diamond Light Source, be upgraded to ensure that the UK's scientific community remains competitive by contributing to cutting-edge global research.


