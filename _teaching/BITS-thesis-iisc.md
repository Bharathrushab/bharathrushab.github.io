---
title: "Undergraduate Research Intern"
collection: teaching
type: "Undergraduate Thesis"
permalink: /teaching/BITS-thesis-iisc
venue: "Computational Data Science Department, Indian Institute of Science"
date: 2019-06-01
location: "Bangalore, India"
---

Research Intern in the Medical Image Processing (MIG) lab headed by Prof.[Phaneendra Yalavarthy](http://cds.iisc.ac.in/faculty/yalavarthy/) of the Computational Data Science department at IISc, Bangalore. 

Research Overview
======

The MIG lab led by Prof.[Phaneendra Yalavarthy](http://cds.iisc.ac.in/faculty/yalavarthy/) mainly focusses on deep learning and computational methods in medical imaging, medical image processing (reconstruction/analysis), physiological signal processing, photoacoustic imaging, and diffuse optical imaging and closely related works. 
* **TEM Image Reconstruction Project:**
    * The Digital Rock and Image Analysis group in Shell Technology Centre, Bangalore develops and uses image processing techniques to study the microstructure of porous media and build physics models to accelerate research and development cycles for Shell businesses. Examples of the porous media systems include 2-D or 3-D images of rocks and catalyst pellets. They have active projects to develop capability in areas of image classification, segmentation, physics based modelling and image reconstruction for different imaging modalities. 
    * One of the aspiration of their program in catalysis domain is to be able to process Transmission Electron Microscopy (TEM) images acquired at different tilt angles to obtain a three dimensional tomographic volume which can be further analysed for pore connectivity, catalyst active site distribution, detailed characterization and simulation. Three dimensional imaging of catalyst particles scanned at nm resolution would allow accurate analysis of active catalyst particles dispersion on support sites, reactant accessible surface area for reactions and connectivity of the porous support matrix. However, the tomographic reconstruction software available with commodity hardware generates subpar images which are inadequate for accurate analysis of the 3D volume generated. 
    * My efforts were directed towards benchmarking multiple open source available softwares such as IMOD, ASTRA for the reference sample images generated internally and come up with a workable combination of tools and algorithms. The problem involved adequate alignment and reconstruction methods.

* **MRI Image Reconstruction Project:**
   * Another project at the Medical Image Processing lab at IISc Bangalore is related to Magnetic Resonance Imaging (MRI) image reconstruction. The medical costs and stress to patients during MRI can be greatly reduced by taking fewer measurements. The main challenges in this compressed sensing methodology is creating a sampling matrix and the reconstruction algorithms. 
  * Many deep learning methodologies have been developed based on the insights of the optimization-based traditional methods and the accuracy of network-based methods. The aim is to use the publicly available fast-MRI dataset to evaluate the performance of network-based and optimization methods.


My Contributions
======
* **TEM Image Reconstruction Project:**
  * Apart from Prof. Phaneendra Yalavarthy from IISc Bangalore, I worked closely with Dr.Umang Agarwal and Dr.Valliappan at the Shell Technology Centre, Bangalore - India. My role in this project was to create a model which will successfully eliminate the misalignments in the TEM data for accurate volume reconstruction. For this purpose, I researched various  algorithms and softwares for feature extraction, feature segmentation, volume visualization and volume reconstruction. Generally, cross-correlation based approaches are used for marker-less TEM datasets but they are not known to give good results in all instances. 
  * We proposed a better solution that works for both marker-less and fiducial marker datasets. It is based on identifying and partitioning distinct feature/marker regions and segmenting the parts for better feature extraction. Then I used ASTRA toolbox to back project the series and reconstruct the volume.

* **MRI Image Reconstruction Project:**
  * For the second project, I worked on implementing current reconstruction models and developing a faster and accurate deep network-based algorithm to study and improve the compressed sensing based reconstruction of Magnetic Resonance Imaging (MRI) data.
