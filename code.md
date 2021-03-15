---
layout: page
title: Code
permalink: /code/
---
<h1> Particle Filter for Tracking </h1>
I wrote a framework for Particle Filter-based tracking from colour images. The framework utilizes importance sampling and dynamical system model for object tracking. It is capable of tracking in the presence of short-lived occlusion.
<br>
<table><tbody><tr><td><h4>Particle Filter</h4></td>
<td>{% include image.html url="/images/particleFilter/particleFilterBallGT.gif" caption="Input Sequence" width=300 align="center" %}</td>
<td><img src="/images/white.jpg" alt="space" style="width:50px"></td>
<td>{% include image.html url="/images/particleFilter/particleFilterBall.gif" caption="Particle Filter-based tracking" width=300 align="center" %}</td></tr></tbody></table>
<br>
Code available at: <a href="https://github.com/masaddev/OpenCVParticleFilter">https://github.com/masaddev/OpenCVParticleFilter</a>
<!-- More details at: <a href="http://seevisionc.blogspot.co.uk/2016/04/particle-filtering.html">http://seevisionc.blogspot.co.uk/2016/04/particle-filtering.html</a> and at: <a href="http://seevisionc.blogspot.co.uk/2016/08/particles-explained-using-gifs.html">http://seevisionc.blogspot.co.uk/2016/08/particles-explained-using-gifs.html</a> -->
<br>
<h1> OpenCVRandomForest: Framework for Multi-variate Random Forest Regression in OpenCV </h1>
I wrote this framework as part of the application for my research. The code is written in C++ using OpenCV, enabling real-time execution. I have specifically made sure to utilize memory in an efficient way. The framework runs in real-time on mobile platforms running windows. It also contains a simple utility function used to explore the individual tree structures.
<br>
<table><tbody><tr><td><h4>OpenCVRandomForest</h4></td>
<td><img src="/images/white.jpg" alt="space" style="width:100px"></td>
<td>{% include image.html url="/images/OpenCVRandomForest/rfTrees.gif" caption="Visualization of Tree structures" width=350 align="center" %}</td>
</tr></tbody></table>
<br>
Code available at: <a href="https://github.com/masaddev/OpenCVRandomForest">https://github.com/masaddev/OpenCVRandomForest</a>
<br>
<h1> OpenCVKinect: Acquiring Kinect Data Streams in OpenCV </h1>
I have worked with Kinect Sensor for a number of projects. Some of these required me to collect big datasets. The existing methods that I found for acquring and storing data from Kinect Sensor were all either too complicated or required a lot of libraries. The biggest issue was that once I acquired data I had to save it before implementing any computer vision based algorithm as it was not directly accessible within commonly used computer vision libraries. I wrote a library using OpenCV (C++) that enabled acquisition of Kinect data streams directly into OpenCV cv::Mat format. This library has since been used by a number of researchers and students to acquire data and process it using OpenCV library in real-time. 
<br>
<table><tbody><tr><td><h4>OpenCVKinect</h4></td>
<td>{% include image.html url="/images/OpenCVKinect/colorAGif.gif" caption="Colour Image" width=300 align="center" %}</td>
<td><img src="/images/white.jpg" alt="space" style="width:50px"></td>
<td>{% include image.html url="/images/OpenCVKinect/colorizedDepthAGif.gif" caption="Depth Image" width=300 align="center" %}</td></tr></tbody></table>
<br>
Code available at: <a href="https://github.com/masaddev/OpenCVKinect">https://github.com/masaddev/OpenCVKinect</a>
<br>
<h1> OpenCVGMM: Gaussian Mixture Model in OpenCV </h1>
In my spare time I have also implemented Gaussian Mixture Model using Expectation Maximization in OpenCV C++. This is a straightforward implementation that I used in some clustering problems. The key attractive idea of GMM is its probabilistic approach, where a sample can coexist in multiple clusters with varying probabilities.
<br>
<table><tbody><tr><td><h4>OpenCVGMM</h4></td>
<td>{% include image.html url="/images/OpenCVGMM/GMM.gif" caption="GMM Clustering" width=300 align="center" %}</td>
<td><img src="/images/white.jpg" alt="space" style="width:50px"></td>
<td>{% include image.html url="/images/OpenCVGMM/GMM2.gif" caption="GMM Clustering" width=300 align="center"%}</td></tr></tbody></table>
<br>
Code available at: <a href="https://github.com/masaddev/OpenCVGMM">https://github.com/masaddev/OpenCVGMM</a>

