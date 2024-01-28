<div align="center">  <h1> CSC_quantification: A MATLAB-based tool for cervical spinal cord atrophy quantification using MRI images </h1></div>

<h4> Author: Mouna Sahnoun, Ph.D, mounasahnoun2@gmail.com
Advanced Technologies for Medecine & Signal 'ATMS' Research Laboratory, National Engineering School of Sfax-Sfax University-Tunisia </h4>


<h2> Brief Description of CSC_quantification </h2>
CSC_quantification is a software tool developed on MATLAB, specifically designed to help neurologists measuring Cervical Spinal Cord atrophy and tracking Multiple Sclerosis  patients. 

<h2> System Requirements</h2>
CSC_quantification is developed on MATLAB R2023b, thus its system requirements are identical to those of MATLAB. The following are the minimum system requirements for running CSC_quantification:

<h3> Operating Systems </h3>
<i> - For Windows:  </i>
Windows 11, Windows 10 (version 21H2 or higher), Windows Server 2019, Windows Server 2022.


<i> - For Linux </i>
Ubuntu 22.04 LTS, Ubuntu 20.04 LTS, Debian 11, Red Hat Enterprise Linux 9, Red Hat Enterprise Linux 8 (minimum 8.6), Red Hat Enterprise Linux 7 (minimum 7.9), SUSE Linux Enterprise Desktop 15, SUSE Linux Enterprise Server 12 (minimum SP2), SUSE Linux Enterprise Server 15.

<i> - For Mac </i>
macOS Sonoma (14), macOS Ventura (13), macOS Monterey (12.6),

<h3> Processor </h3>
Minimum: Any Intel or AMD x86-64 processor with two or more cores
Recommended: Any Intel or AMD x86-64 processor with four or more cores and AVX2 instruction set support 

<h3> RAM </h3>
Minimum: 8 GB, Recommended: 16 GB

<h3> Storage </h3>
3.8 GB for just MATLAB; 4-6 GB for a typical installation; 23 GB for an all products installation. An SSD is strongly recommended

<h3> Graphics </h3>
No specific graphics card is required, but a hardware accelerated graphics card supporting OpenGL 3.3 with 1GB GPU memory is recommended.

<h2> Installation </h2>

The software does not need any installation. 
Add the whole repository to your Matlab search path by addpath.m or by Home -> Set Path -> Add Folder.
To read MRI image, SPM is needed. In fact, SPM is an academic software toolkit for the analysis of functional imaging data, for users familiar with the underlying statistical, mathematical and image processing concepts. It is made freely available to the imaging community, to promote collaboration and a common analysis scheme across laboratories. The software represents the implementation of the theoretical concepts of Statistical Parametric Mapping in a complete analysis package. The SPM software is a suite of (MATLAB) functions and subroutines with some externally compiled C routines. SPM was written to organise and interpret our functional neuroimaging data.
More details about SPM and link to download are available <a href="www.fil.ion.ucl.ac.uk/spm">here</a>  

#Sample File is stored in the folder "CSC_quantification". 
Open the main matlab file 'Patient_Information.m' and Click Run. Folder organization and quick start guide is included in CSC_quantification Documentation file in documentation folder.

