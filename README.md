# Coherent-Diffraction-Imaging
**General physical background**:

Our investigation primarily focused on the Coherent diffraction imaging (CDI) experiment in Diamonds I-13 branchline. CDI is a lensless tomographic technique that measures the diffraction pattern of x-rays that have scattered off of a nanoscaled sample (e.g.nanotube). From this diffraction pattern it is possible to reconstruct a highly resolved image of the sample and thus is a widely used technique in both material and biomedical sciences.

In CDI the resolution of the image is dependent solely on the coherence of the incoming x-ray beam. However, a major drawback with CDI is that by measuring the scattered intensity distribution all phase information of the x-ray beam is lost. Thus information of the sample is also lost and must be iterated over to
retrieve an image of the sample.

**The basic idea of the algorithm**:

The two phase retrieval algorithms presented here are Error Reduction and Gerchberg–Saxton algorithms. I have focused mainly on evaluating the equipment performance of the I-13-1 branchline’s coherent diffraction imaging experiment from Diamond Light Source using the Error Reduction algorithm. 

**1.The model used an iterative feedback algorithm known as the oversampling algorithm to reconstruct the image off a generated intensity distribution.**

**2.The chi-square between the generated images and the original sample image was measured to determine the similarities per iteration.**

**3.A Comparison was made between both Diamond 1, Diamond 2 and an ideal coherent beam. (see files: Results of Diamond I.ipynb, Results of Diamond II.ipynb, Phase_retrieval_algorithm(coherent_lights).ipynb)**



