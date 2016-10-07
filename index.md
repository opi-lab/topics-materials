---
layout: default
title: Computer Vision
---

# Special Topics in Materials Engineering

### Second semester 2016

Andrés Marrugo, PhD
*Universidad Tecnológica de Bolívar*

##  Aims and Scope

This module is an introduction to optical techniques for shape and deformation measurements. It is aimed at graduate students in the Faculty of Engineering. We will focus on the practical and theoretical aspects of optical metrology in experimental mechanics.

At the end of the lectures, one would be able to:

- Have clear idea of challenges in optical metrology for shape and deformation measurements.
- Understand many different optical metrology techniques.
- Implement several image processing algorithms for optical measurements.
 


## Useful Resources

Several of the techniques that we will study are to be implemented in MATLAB. Please follow the tutorials and get acquainted with the programing environement. 

### Tutorials, review materials

- [MATLAB tutorial](matlab.intro.html)
- More MATLAB tutorials: [basic operations][bo], [programming][pro], [working with images][wim]
 
[bo]: matlab_ops_tutorial.m
[pro]:matlab_prog_tutorial.m
[wim]: matlab_image_tutorial.m

### MATLAB reference

- [MATLAB guide from Mathworks](http://www.mathworks.com/access/helpdesk/help/techdoc/matlab.html)
- [MATLAB image processing toolbox](http://www.mathworks.com/access/helpdesk/help/toolbox/images/)
- [Writing fast code](http://www.mathworks.com/matlabcentral/fileexchange/5685)


## Outline

This is a new course, this website will be updated as we go along.

### Lecture 1: Introduction

We will be discussing the main aspects and motivation for optical techniques in experimental mechanics.

[Lecture 1 slides]()

### Lecture 2: Basic Optical Principles and Imaging Systems

We will be studying the main aspects about perspective projection and the pinhole camera model.

[Lecture 2 slides]()

#### Reading

- [Forsyth and Ponce 1st chapter](https://www.dropbox.com/s/mfol1581hpd6fwy/Forsyth-Ponce-chapter-01.pdf?dl=0)
- [Camera geometry and parameters](https://www.dropbox.com/s/2olqadczmsoevo7/01-lectura-geometria-camaras.pdf?dl=0)

### Assignment 1

In this assignment you will study the basics of projective geometry. You will study the representations of points lines and planes, as well as transformations. **The assignment is due on 2016-09-02 at 11:00 pm.** The assignment and the data:

- [Assignment 1](computer-vision-assignment1.pdf)
- [Assignment data](assignment1data.zip)

[**Upload link**](https://www.dropbox.com/request/kcbzM88o03DyAlpOLBtb)

#### Supporting material

- [Lecture notes by Magnus Oskarsson](alllectures.pdf)
- [Homogeneous Coordinates and Transformations of the Plane](9781852338015-c1.pdf)
- [Projective Geometry and Transformations in 2D](Hartley-Zisserman-chapter-02.pdf)


### Lecture 3: Cameras

Cameras with lenses and properties. Thin lens formula, depth of field, field of view, and distorsions.

[Lecture 3 slides](https://www.dropbox.com/s/lmbqj877zpi8u7r/lec03_camera.pdf?dl=0)


### Lecture 4: Color

We will discuss the physics of color, human color perception and models of image color.

[Lecture 4 slides](https://www.dropbox.com/s/pr8pvn0pubdmj1j/lec04_color.pdf?dl=0)

#### Reading

- [Forsyth and Ponce 3rd chapter](https://www.dropbox.com/s/ggba6dvj9u1bcw8/Forsyth-Ponce-chapter-03.pdf?dl=0)

### Lecture 5: Linear Filtering

Linear filters, convolution kernel, smoothing and sharpening.

[Lecture 5 slides](https://www.dropbox.com/s/bii2lkpdl3y24rv/lec05_filter.pdf?dl=0)

#### Reading

- [Forsyth and Ponce 4th chapter](https://www.dropbox.com/s/oojl3uuwlj8mohk/Forsyth-Ponce-chapter-04.pdf?dl=0)

### Lecture 6: Frequency representation, pyramids and filter banks.

In this lecture we will discuss the different representation for images and the sampling problems.

[Lecture 6 slides - frequency](https://www.dropbox.com/s/02a64pfpd59m5xi/lec06_frequency.pdf?dl=0)
[Lecture 6 slides - pyramids](https://www.dropbox.com/s/ladbcvtrek4oro7/lec06_pyramids.pdf?dl=0)

#### Reading

- [Forsyth and Ponce 4th chapter](https://www.dropbox.com/s/oojl3uuwlj8mohk/Forsyth-Ponce-chapter-04.pdf?dl=0)

### <a name="QL1_6"></a> <mark>Questions Lectures 1-6</mark>

If you have worked out the lecture questions, please send them to the following [link.](https://www.dropbox.com/request/0giihDfxx7vb1O4rIDYz)

### Assignment 2

The goal of this assignment is to learn to work with images in MATLAB. **The assignment is due on 2016-09-24 at 11:59 pm.** The assignment and the data:

- [Assignment 2](assignment2)

[**Upload link**](https://www.dropbox.com/request/HNjyNE0MMbHMx0qeUMrX)

### Lecture 7: Edge Detection

We will introduce the general approach towards image edge detection.

[Lecture 7 slides](https://www.dropbox.com/s/jzgv403hpwe8uo1/lec06_edge.pdf?dl=0)

#### Reading

- [Forsyth and Ponce 5.1-5.2](https://www.dropbox.com/s/vzkm4sje4uvrpy7/Forsyth-Ponce-chapter-05-1-2.pdf?dl=0)

### Lecture 8: Corner Detection

We will introduce the general approach towards image edge detection.

[Lecture 8 slides](https://www.dropbox.com/s/ibgtdylezx72abz/lec08_corner.pdf?dl=0)       
[Harris corner detector](harris.m)      

#### Reading

- [Forsyth and Ponce 5.1-5.2](https://www.dropbox.com/s/52hempwwv2gbypn/Forsyth-Ponce-chapter-05-3.pdf?dl=0)

### Lecture 9: SIFT

In this lecture we will discuss Scale-Invariant Keypoints.

[Lecture 9 slides](https://www.dropbox.com/s/v60jegnvetck34u/lec09_sift.pdf?dl=0)

### <mark>Assignment 3</mark> 

The goal of this assignment is to implement a Laplacian blob detector. **The assignment is due on 2016-10-15 at 11:59 pm.** The assignment and the data:

- [Assignment 3](assignment3)

[**Upload link**](https://www.dropbox.com/request/0fDrePHzilihx3YHBBP8)

### Lecture 10: Optical Flow

We will introduce motion estimation in computer vision.

[Lecture 10 slides](https://www.dropbox.com/s/6db7s4etomd0p21/lec10_optical_flow.pdf?dl=0)       

#### Reading

- [Forsyth and Ponce 11.1](https://www.dropbox.com/s/1kmiy3gtli1i5xl/Forsyth-Ponce-chapter-11-1.pdf?dl=0)

### Lecture 11: Fitting

In this lecture we will discuss the main aspects of fitting data to a parametric model, especially under the assumption of noisy data.

[Lecture 11 slides](https://www.dropbox.com/s/dqx065cez99pim2/lec11_fitting.pdf?dl=0)       

#### Reading

- [Forsyth and Ponce 10.2](https://www.dropbox.com/s/3ld7ayedcj4u2bz/Forsyth-Ponce-chapter-10.pdf?dl=0)
- [Forsyth and Ponce 22.1](https://www.dropbox.com/s/ufecs7h22109r1m/Forsyth-Ponce-chapter-22-1.pdf?dl=0)
