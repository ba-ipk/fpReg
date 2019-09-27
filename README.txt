Feature Point based Multimodal Plant Image Registration - fpReg v.0.1


1. Introduction

fpReg was developed within the scope of a research study [1] aiming to investigate the parameter-dependent performance of seven feature point (FP) based methods for automated alignment of multimodal plant images. 

2. Key Features

The tool performs affine registration of a pair of selected images (for example, FLU and VIS images of the same plant shoot) using seven different FP registration techniques (i.e. SURF, FAST, MSER, Harris, MinEigen, BRISK, KAZE) as well as their combination.

3. Files

Interested users can download free pre-complied binaries of the kmReg tool for Windows x64 and Linux OS:  

fpReg0.1_win.zip - fpReg for Windows x64 (~300MB),
fpReg0.1_linux.zip - fpReg for Linux (~300MB).

By downloading, installing and/or using this software the user agrees with the End-User License Agreement, please read EULA.txt attached to this repository.

This software requires MATLAB run time libraries (version 2018b) to be installed from https://www.mathworks.com/products/compiler/matlab-runtime.html:

- Windows x64: http://ssd.mathworks.com/supportfiles/downloads/R2018b/deployment_files/R2018b/installers/win64/MCR_R2018b_win64_installer.exe (~2GB),
- Linux: http://ssd.mathworks.com/supportfiles/downloads/R2018b/deployment_files/R2018b/installers/glnxa64/MCR_R2018b_glnxa64_installer.zip (~2GB).

Windows users should also install the MS run-time components from the following link:

https://www.microsoft.com/en-us/download/details.aspx?id=48145

A few examples of multimodal plant images (such as original and segmented FLU/VIS images) are included in the above *.zip archives.
Further examples of plant images can be downloaded from larger file repositories, for example  

http://dx.doi.org/10.5447/IPK/2017/24
http://dx.doi.org/10.5447/IPK/2017/25
http://dx.doi.org/10.5447/IPK/2017/26

4. How to use

After unpacking the above *.zip file into a dedicated folder, run the executable (e.g., fpReg.exe on Windows, included *.sh script on Linux).
Select a pair corresponding plant images to be registered that can be found in the folder "examples_of_plant_images" (e.g., Maize_side_vis_seg_old_1.png and Maize_side_flu_seg_old_1.png). 
As soon as two images are loaded, the program will automatically try to perform image co-registration and shows the result. 
To change between different registration methods and options, select the corresponding buttons on the GUI window.

5. References

[1] Henke, M., Junker, A., Neumann, K., Altmann, T., Gladilin, E., <i>Comparison of Feature Point Detectors for Multimodal Image Registration in Plant Phenotyping (unpublished)

(C) 2018, Image Analysis Group, IPK Gatersleben
http://www.ipk-gatersleben.de/signature/impressum/
