<h1> <div align="center"> User’s Guide </div> </h1> 

<div align="center">  <h3> CSC_quantification: A MATLAB-based tool for Cervical Spinal Cord atrophy quantification using MRI images </h3></div>
<div align="center">  ------------------------------------------------------------------------------------------------------------------------------------------------------------- </div>

<h2> Brief Description of AnIMAGE </h2>
CSC_quantification is a software tool developed on MATLAB, specifically designed to help neurologists measuring Cervical Spinal Cord atrophy and tracking Multiple Sclerosis  patients. 

<h2> System Requeriments</h2>
CSC_quantification is developed on MATLAB R2023b, thus its system requirements are identical to those of MATLAB. The following are the minimum system requirements for running CSC_quantification:

<h3> Operating Systems </h3>
----------------------------------------
<i> for Windows  </i>
Windows 11
Windows 10 (version 21H2 or higher)
Windows Server 2019
Windows Server 2022
-----------------------------
<i> for Linux </i>
Ubuntu 22.04 LTS
Ubuntu 20.04 LTS
Debian 11
Red Hat Enterprise Linux 9
Red Hat Enterprise Linux 8 (minimum 8.6)
Red Hat Enterprise Linux 7 (minimum 7.9)
SUSE Linux Enterprise Desktop 15
SUSE Linux Enterprise Server 12 (minimum SP2)
SUSE Linux Enterprise Server 15
-----------------------------
<i> for Mac </i>
macOS Sonoma (14)
macOS Ventura (13)
macOS Monterey (12.6)

<h3> Processor </h3>
----------------------------------------
Minimum: Any Intel or AMD x86-64 processor with two or more cores
Recommended: Any Intel or AMD x86-64 processor with four or more cores and AVX2 instruction set support 
Note: A future release of MATLAB will require a processor with AVX2 instruction set support

<h3> RAM </h3>
----------------------------------------
Minimum: 8 GB
Recommended: 16 GB

<h3> Storage </h3>
----------------------------------------
3.8 GB for just MATLAB
4-6 GB for a typical installation
23 GB for an all products installation
An SSD is strongly recommended

<h3> Graphics </h3>
----------------------------------------
Graphics
No specific graphics card is required, but a hardware accelerated graphics card supporting OpenGL 3.3 with 1GB GPU memory is recommended.





To run the AnImage GUI, it is essential to have the CST_App folder downloaded from the repository, it contains the necessary files that the software use to function properly. Between these, the Application Programming Interface (API) files that connect the CST STUDIO Suite with Matlab extracted via (https://github.com/hgiddenss/CST_App). In addition, as well as other files that enable the users to access in the AnImage GUI from Matlab.

Finally, if you wish to perform an electromagnetic analysis on a structure designed with AnIMAGE, you must have previously installed the CST Studio software on your computer, if it is not installed, the Matlab script “CST MicrowaveStudio.m” will not run correctly Instructions:

Instructions for installing the software and generating microstrip antennas with complex structures are provided below.






#Installation

Add the whole repository to your Matlab search path by addpath.m or by Home -> Set Path -> Add Folder.
Open main.m and Click Run.
#Sample File is stored in the folder "CSC_quantification"

#Manual Further details about how to use 'SC_quantific' can be found here SC_quantific_manual.pdf

Author Mouna Sahnoun, Ph.D. mounasahnoun2@gmail.com

Advanced Technologies for Medecine & Signal 'ATMS' Research Laboratory, National Engineering School of Sfax-Sfax University-Tunisia
