---
layout: page
title: "Demo Download"
comments: true
sharing: true
footer: true
---

{% img /workshop/images/ImageStitch_thumb.png 890 280 %}

####Download:
[Demo_macosx]({{ root_url }}/workshop/image-stitch/Demo_mac.zip)
[Demo_win32]({{ root_url }}/workshop/image-stitch/Demo_win32.zip)

- - -
###Prerequisites for Deployment 

. Verify the MATLAB Compiler Runtime (MCR) is installed and ensure you    
  have installed version 8.0 (R2012b).   

. If the MCR is not installed, do the following:
  (1) enter
  
      >>mcrinstaller
      
      at MATLAB prompt. The MCRINSTALLER command displays the 
      location of the MCR Installer.

  (2) run the MCR Installer.

Or download the Macintosh version of the MCR for R2012b 
from the MathWorks Web site by navigating to

   http://www.mathworks.com/products/compiler/mcr/index.html

###For mac or unix users
run_mac_pipei.sh (shell script for temporarily setting environment variables and 
 executing the application)
   -to run the shell script, type
   
       ./run_mac_pipei.sh <mcr_directory> <argument_list>
       
    at Linux or Mac command prompt. <mcr_directory> is the directory 
    where version 8.0 of MCR is installed or the directory where 
    MATLAB is installed on the machine. <argument_list> is all the 
    arguments you want to pass to your application. For example, 

    If you have version 8.0 of the MCR installed in 
    /mathworks/home/application/v80, run the shell script as:
    
       ./run_mac_pipei.sh /mathworks/home/application/v80
       
    If you have MATLAB installed in /mathworks/devel/application/matlab, 
    run the shell script as:
    
       ./run_mac_pipei.sh /mathworks/devel/application/matlab
