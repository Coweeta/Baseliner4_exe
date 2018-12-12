# Baseliner_4_01.exe; version released 2018.12.12
Functionally identical to previous version, but now will correct for common time-step errors, including missing or duplicate time-steps and midnight time/day errors (if midnight is recorded as 00:00 it should be the first time step of a day, else if 24:00 it should be the last time-step of the day).
Version compiled using MATLAB R2018b, so may require more recent version of MATLAB Runtime (see below), or may work as stand alone applicaiton.

# Baseliner4_exe
Stand-alone executable program for Windows (no MATLAB required)

From the Baseliner4_exe folder in github, you have two options to install the software on your computer.

Option 1) Download and run the MyAppInstaller_web.exe file. It will guide you through the installation process, which will include downloading and installing MATLAB Runtime. This option downloads components from the web and may be slow, depending on your computer's connectivity. 

Option 2) First go to http://www.mathworks.com/products/compiler/mcr/index.html and install MATLAB Runtime R2015b. Then download and run Baseliner.exe file.  

Sample data have also been provided to test out the program.
