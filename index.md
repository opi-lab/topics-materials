---
layout: default
title: Special Topics in Materials Engineering
---

# Special Topics in Materials Engineering

### Second semester 2016

Andrés Marrugo, PhD   
Jairo Useche, PhD   
*Universidad Tecnológica de Bolívar*

Invited lecturers: 

- Marcelo Pagnola, Universidad de Buenos Aires (Argentina)
- Marcin Górski, Silesian Technical University (Poland)

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

We will be discussing the main aspects and motivation for optical techniques in experimental mechanics. A brief discussion on accuracy and precision related to uncertainty in physical measurements. 

[Lecture 1 slides](https://www.dropbox.com/s/janth8jr4kjyptt/Lecture_01.pdf?dl=0)

#### Reading

- [A note on device calibration](https://www.dropbox.com/s/euy6n11l887q0sx/03-NoteDeviceCalibration.pdf?dl=0)
- [A paper on characterization of hyperelastic materials based on optical methods](https://www.dropbox.com/s/5shl2zn33fifvo6/Polymer_Testing_Sasso_2008.pdf?dl=0)

### Lecture 2: Basic Optical Principles and Imaging Systems

We will be studying the basic optical principles, the nature of light, light as a wave, polarization, wavefront propagation, and image formation with lenses.

[Lecture 2 slides](https://www.dropbox.com/s/e6cy8hilcr7t4bv/Lecture_02.pdf?dl=0)

#### Reading

- [Gasvik 1st chapter](https://www.dropbox.com/s/bcsmtywsz2dkpmt/01-gasvik-basics.pdf?dl=0)

### Lecture 3: Optical interferometry.

We will be studying the fundamentals of optical interferometry.

[Lecture 3 slides](https://www.dropbox.com/s/t5vccdwyr3w5r1b/Lecture_03.pdf?dl=0)

#### Reading

- [Gasvik 3rd chapter](https://www.dropbox.com/s/9dkoqu20j7p3dgd/02-gasvik-inteference.pdf?dl=0)

### Lecture 4: 

We will be studying the fundamentals of optical interferometry.

[Lecture 4 slides](https://www.dropbox.com/s/aa0uda9z7p6llif/Lecture_04.pdf?dl=0)

#### Reading

- [Phase shifting systems](https://www.dropbox.com/s/8vot6dsvxd029f1/03-phase-shifting-systems-kevin-g-harding-handbook-of-optical-dimensional-metrology.pdf?dl=0)

### Lecture 5: Moiré and Triangulation 

Measuring in-plane and out-of-plane displacements.

[Lecture 5 slides](https://www.dropbox.com/s/ne4l921c6q0k754/Lecture_05.pdf?dl=0)

#### Reading

- [Moiré](https://www.dropbox.com/s/rux5i1qnt4blmgj/07-gasvik-moire.pdf?dl=0)


### Assignment 1

In this assignment you will study the basics of 3D reconstruction by fringe projection. Submit a report in PDF with calculation and the recovered surface. To display use the command ``mesh(X,Y,Z)``, where ``Z`` is the recovered surface in mm and ``X, Y`` are the transversal field in mm. You can calculate ``X,Y`` with the command ``[X,Y]=meshgrid()`` and from the lens equation. In the report include a 1-page analysis of one of the three papers in the supporting material section. 

**The assignment is due on 2016-11-5 at 11:00 pm.** The assignment and the data:



- [Assignment 1](https://www.dropbox.com/s/hf2y1tb2yamjnep/Simul_Franjas_Dec.pdf?dl=0)
- [Assignment data](https://www.dropbox.com/s/99w829u7doo77mu/Archive.zip?dl=0)

[**Upload link**](https://www.dropbox.com/request/x68PXNrXRnfvmZy8a6Sr)

#### Supporting material

- [Barrera_2013](https://www.dropbox.com/s/85dt1vri6s29rfk/Barrera_2013.pdf?dl=0)
- [Revista_INGE_CUC_Gonzalez_2012](https://www.dropbox.com/s/pvvsasv2h8zdlje/Revista_INGE_CUC_Gonzalez_2012.pdf?dl=0)
- [Revista_Investigaciones_Aplicadas_Arciniegas_2015](https://www.dropbox.com/s/2bc8q3cj5a4icm1/Revista_Investigaciones_Aplicadas_Arciniegas_2015.pdf?dl=0)

### Lecture 6: Measurement of Strain by Digital Image Correlation

In this lecture we discuss the principles of Digital Image Correlation for measuring in-plain deformations and strains. We also analyze simulation and experimental data using .

[Lecture 6 slides](https://www.dropbox.com/s/5ailnloacho9flg/Lecture_06.pdf?dl=0)
[Linear filtering slides](https://www.dropbox.com/s/9fyng6rwqc1qk32/lec05_filter.pptx?dl=0)
[Template matching slides](https://www.dropbox.com/s/lxgij6tzkc44xpw/06-filtros-piramides-plantillas.pdf?dl=0)
[Optical flow slides](https://www.dropbox.com/s/6db7s4etomd0p21/lec10_optical_flow.pdf?dl=0)

### Assignment 2

In this assignment you will study the basics strain measurement by digital image correlation. You have to analyze the two data-sets with the Improved Digital Image Correlation (DIC) toolbox. Follow the tutorial to analyze the first data-set, analyze the second data-set and compute the poisson ratio. Report your findings in a report in PDF. 


**The assignment is due on 2016-11-19 at 11:00 pm.** The assignment and the data:

[Matlab DIC code](matlab-dic-code.zip)
[Data set 1](dataset01.zip)
[Data set 2](dataset02.zip)
