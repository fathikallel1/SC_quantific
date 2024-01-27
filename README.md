<h1> <div align="center"> User’s Guide </div> </h1> 

<div align="center">  <h3> CSC_quantification: A MATLAB-based tool for Cervical Spinal Cord atrophy quantification using MRI images </h3></div>
<div align="center">  ------------------------------------------------------------------------------------------------------------------------------------------------------------- </div>

<h3> Brief Description of AnIMAGE </h3>
CSC_quantification is a software tool developed on MATLAB, specifically designed to help neurologists measuring Cervical Spinal Cord atrophy and tracking Multiple Sclerosis  patients. 


to facilitate the design process of microstrip antennas with complex geometries. This software enables the creation of high-performance antennas with more design options, while its user-friendly interface simplifies the design process and streamlines design calculations, saving designers significant time and effort. Additionally, AnIMAGE allows for the exportation of complex geometries, providing the ability to simulate the electromagnetic behavior of these antennas in CST Studio. This software is particularly useful for designers looking to create antennas with complex geometries such as fractals or other structures derived from images, as it offers them innovative ways to design microstrip antennas.

System Requeriments
AnIMAGE is developed on MATLAB R2022b, thus its system requirements are identical to those of MATLAB. The following are the minimum system requirements for running AnIMAGE:

Processor: Any Intel-based Mac with four cores

RAM: 4 GB minimum, but 8 GB is recommended

Hard disk space: 20 GB of HDD space for MATLAB only, 30 GB for a typical installation.

Operating system: macOS 10.15 (Catalina), macOS 10.14 (Mojave), macOS 10.13 (High Sierra)

Graphics: A GPU with OpenGL 3.3 or later support is recommended for using the GPU acceleration feature.

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
