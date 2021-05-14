# update 2021.5.14: Baseliner download with MATLAB Runtime included
Baseliner_4.21runtime.exe: You can download and run this installer without needing an separate download of the Runtime program

# Baseliner_4.21.exe; version 2021 released 2021.05.04
Updated version of the stand-alone Windows application. Analogous to the MATLAB-based Baseliner_4_02 version (released 2020.07.07) https://github.com/Coweeta/baseliner4
Version compiled using MATLAB R2021a on a Windows10 machine.

Download and run either 
Baseliner_4.21.exe
or
MyAppInstaller_web.exe

Each file will run an installer program (that will also prompt you to download the MATLAB Runtime program).

Thanks to Chainey Boroski at Duke University for compiling the current version!

please contact Chris Oishi with questions or feedback: andrew.c.oishi@usda.gov

# Baseliner_4_01.exe; version released 2018.12.12
Functionally identical to previous version, but now will correct for common time-step errors, including missing or duplicate time-steps and midnight time/day errors (if midnight is recorded as 00:00 it should be the first time step of a day, else if 24:00 it should be the last time-step of the day).
Version compiled using MATLAB R2018b, so may require more recent version of MATLAB Runtime (see below), or may work as stand alone applicaiton.

please contact Chris Oishi with questions or feedback: andrew.c.oishi@usda.gov

Please use the following reference when citing this software:
Oishi, A.C., Hawthorne, D., and Oren, R. Baseliner: An open-source, interactive tool for processing sap flux data from thermal dissipation probes. Software-X. 5: 139-143. DOI: 10.1016/j.softx.2016.07.003. 

MATLAB source code available at https://github.com/Coweeta/baseliner4

# Baseliner4_exe
Stand-alone executable program for Windows (no MATLAB required)

From the Baseliner4_exe folder in github, you have two options to install the software on your computer.

Option 1) Download and run the MyAppInstaller_web.exe file. It will guide you through the installation process, which will include downloading and installing MATLAB Runtime. This option downloads components from the web and may be slow, depending on your computer's connectivity. 

Option 2) First go to http://www.mathworks.com/products/compiler/mcr/index.html and install MATLAB Runtime R2015b. Then download and run Baseliner.exe file.  

Sample data have also been provided to test out the program.
