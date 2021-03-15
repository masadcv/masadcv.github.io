---
layout: page
title: Research
permalink: /research/
---

# Interests
<h3 style="text-align:center">Probabilistic Regression &#8226; Optimisations for Neural Networks &#8226; Fully-convolutional Neural Network &#8226; Neural Network Compression </h3>

<br>

***

<br>

# Cross-modality Learning using Fully-Convolutional Neural Networks
In this work, we worked on designing, implementing (Python/Tensorflow) and evaluating a fully-convolutional neural network that enabled cross-modality learning for Magnetic Resonance Imaging (MRI). The proposed method generated T2-weighted MRI images from T1. T2-weighted MRI is particularly challenging to acquire due to time, cost constraints as well as significant imaging artefacts. 

Published as workshop paper: [**XmoNet: A Fully Convolutional Network for Cross-Modality MR Image Inference**](/papers/pdf/MICCAIW2018Xmonet.pdf){:target="\_blank"} at [MICCAI 2018 Workshops](http://miccai2018.org/){:target="\_blank"}.

{% include image.html url="/images/xomonet_flowchart.png" caption="XmoNet: A Fully Convolutional Network for Cross-Modality MR Image Inference." width=500 align="center" %}


<br>

***

<br>

# Efficient Hand Orientation and Pose Estimation for Uncalibrated Cameras
For my doctorate thesis, I explored advance non-linear regression methods for estimating hand orientation and pose from uncalibrated colour images. The work aimed to propose machine learning techniques that can generalise well for variations in hand shape, size, style and be independent of camera calibration - hence easily deployable on mobile devices.

I made contributions in terms of novel probabilistic regression methods that enabled to learn from ambiguous datasets where existing regression methods struggled to generalise.

A significant part of my thesis was published as a journal paper titled [**SPORE: Staged Probabilistic Regression for Hand Orientation Inference**](/papers/pdf/CVIU2017SPORE_Regression.pdf){:target="\_blank"} at [CVIU 2017](https://www.journals.elsevier.com/computer-vision-and-image-understanding){:target="\_blank"}.

{% include image.html url="/images/egoCentricAR.gif" caption="Efficient hand orientation and pose estimation for uncalibrated cameras." width=340 align="center" %}


<br>

***

<br>

# Optical Biopsy of Brain Tumours
During my doctorate degree, I worked on research and implementation (Matlab) of a supervised learning method for image-based categorisation of brain tumours. The proposed method characterised brain tissue (normal, low-grade or high-grade tumour) using Magnetic Resonance Spectroscopy (MRS) imaging. We addressed the problem of [partial volume effect](https://en.wikipedia.org/wiki/Partial_volume_(imaging)){:target="\_blank"}. 

Published as conference paper: [**Supervised Partial Volume Effect Unmixing for Brain Tumor Characterization using Multi-voxel MR Spectroscopic Imaging**](/papers/pdf/ISBI2016BrainTumor.pdf){:target="\_blank"} at [ISBI 2016](https://biomedicalimaging.org/2016/){:target="\_blank"}.

{% include image.html url="/images/MRSTumor.PNG" caption="The left two images show a patient’s brain using different MR modalities, and the right image has our technique overlaid, as heatmaps indicating tissue grades." width=600 align="center" %}

<br>

***

<br>

# Hand Gesture Recognition using Microsoft Kinect
My dissertation project for my Master's degree at [The University of Sheffield](http://www.sheffield.ac.uk/){:target="\_blank"} explored hand gesture recognition using depth images from [Microsoft Kinect v1](https://en.wikipedia.org/wiki/Kinect#Kinect_for_Xbox_360_(2010)){:target="\_blank"}. It involved research, design and implementation (C++/OpenCV/OpenNI) on utilising Kinect depth images for dynamic hand gesture recognition. The work proposed a distance-invariant hand cropping method that used the distance of hand to the sensor for adjusting the cropping window. Additionally, a method for addressing quantisation noise in depth images through morphological post-processing steps was proposed. The dynamic hand gestures were divided into pose stages, which were detected using a [Multi-layered Perceptron (MLP)](https://en.wikipedia.org/wiki/Multilayer_perceptron){:target="\_blank"} network on post-processed projections of depth images on x-y, y-z, x-z planes. A simple [Hidden Markov model (HMM)](https://en.wikipedia.org/wiki/Hidden_Markov_model){:target="\_blank"} was used on the output of MLP to recognise the dynamic gesture sequences.

Published as conference paper: [**Kinect Depth Stream Pre-processing for Hand Gesture Recognition**](/papers/pdf/ICIP2013PreprocessDepthHand.pdf){:target="\_blank"} at [ICIP 2013](http://www.2013.ieeeicip.org/ICIP2013/){:target="\_blank"}.
<h3>Distance Invariant Hand Cropping:</h3>
<table style="border:1px solid black;margin-left:auto;margin-right:auto;"><tbody>
<tr>
<td><h4 style="text-align:center">Distance</h4></td>
<td><h4 style="text-align:center">Input</h4></td>
<td><h4 style="text-align:center">Fixed</h4></td>
<td><h4 style="text-align:center">Distance Invariant</h4></td>
</tr>
<td colspan="12"><hr /></td>
<tr>
<td><h4>0.7 meters</h4></td>
<td><img src="/images/HGR/dicrop/hand700mm.png" alt="" style="width:200px"></td>
<td><img src="/images/HGR/dicrop/fxhandcrop700mm.png" alt="" style="width:150px"></td>
<td><img src="/images/HGR/dicrop/dihandcrop700mm.png" alt="" style="width:150px"></td>
</tr>
<td colspan="12"><hr /></td>
<tr>
<td><h4>1.7 meters</h4></td>
<td><img src="/images/HGR/dicrop/hand1700mm.png" alt="" style="width:200px"></td>
<td><img src="/images/HGR/dicrop/fxhandcrop1700mm.png" alt="" style="width:150px"></td>
<td><img src="/images/HGR/dicrop/dihandcrop1700mm.png" alt="" style="width:150px"></td>
</tr></tbody></table>
<br>
<h3>Post-processing for quantisation noise in Kinect depth images:</h3>
<table style="border:1px solid black;margin-left:auto;margin-right:auto;"><tbody><tr><td><h4>Original</h4></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projNoPost700.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projNoPost950.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projNoPost1200.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projNoPost1450.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projNoPost1700.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
</tr>
<td colspan="12"><hr /></td>
<tr><td><h4>Proposed</h4></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projMorph700.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projMorph950.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projMorphInter1200.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projMorphInter1450.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
<td><img src="/images/HGR/quantpost/projMorphInter1700.png" alt="" style="width:200px"></td>
<td><img src="/images/white.jpg" alt="space" style="width:10px"></td>
</tr></tbody></table>

<br>

***

<br>

# Traffic Flow Estimation for Edge Devices
During my Master's degree at [The University of Sheffield](http://www.sheffield.ac.uk/){:target="\_blank"}, I worked on a coursework project for Computer Vision module building a traffic flow estimation algorithm. This project proposed an optimised algorithm targetted for resource constraint hardware, such as [BeagleBoard-xM](https://beagleboard.org/Products/BeagleBoard-xM){:target="\_blank"}. I implemented (C++/OpenCV) a method using [background subtraction](https://en.wikipedia.org/wiki/Background_subtraction){:target="\_blank"}, [morphological post-processing](https://en.wikipedia.org/wiki/Mathematical_morphology){:target="\_blank"} and [image moments](https://en.wikipedia.org/wiki/Image_moment){:target="\_blank"} to detect cars and estimate traffic congestion.
<table style="border:1px solid black;margin-left:auto;margin-right:auto;"><tbody><tr>
<td><img src="/images/trafficFlow/input_image.png" alt="" style="width:200px"></td>
<td><img src="/images/trafficFlow/backgr_image.png" alt="" style="width:200px"></td>
<td><img src="/images/trafficFlow/backgr_sub_image.png" alt="" style="width:200px"></td>
<td><img src="/images/trafficFlow/output_image.png" alt="" style="width:200px"></td>
</tr></tbody></table>

<br>

***

<br>

# Smartphone based Guidance System for Visually Impaired
During my Bachelor's degree at [National University of Computer and Emerging Sciences](http://nu.edu.pk/){:target="\_blank"}, I worked on my dissertation project building a guidance system for visually impaired. This project involved research, design and implementation (Matlab/Android/OpenCV) of a method that used [morphological edge detectors](https://en.wikipedia.org/wiki/Morphological_gradient){:target="\_blank"}, [Hough transform](https://en.wikipedia.org/wiki/Hough_transform){:target="\_blank"} and [RANSAC](https://en.wikipedia.org/wiki/Random_sample_consensus){:target="\_blank"} for detecting [vanishing points](https://en.wikipedia.org/wiki/Vanishing_point){:target="\_blank"} from 2D uncalibrated colour images of a straight path. The detected vanishing points were used to provide guidance on the deviation of a visually impaired person from a straight path. 

Published as conference paper: [**Smartphone based Guidance System for Visually Impaired Person**](/papers/pdf/IPTA2012_GSVI.pdf){:target="\_blank"} at [IPTA 2012](http://www.ipta-conference.com/){:target="\_blank"}.
<table style="border:1px solid black;margin-left:auto;margin-right:auto;"><tbody><tr>
<td><img src="/images/GSVI/GuidanceDecision1.png" alt="" style="width:200px"></td>
<td><img src="/images/GSVI/GuidanceDecision2.png" alt="" style="width:200px"></td>
<td><img src="/images/GSVI/GuidanceDecisionHall.png" alt="" style="width:200px"></td>
<td><img src="/images/GSVI/GuidanceDecisionHighway.png" alt="" style="width:200px"></td>
</tr></tbody></table>

