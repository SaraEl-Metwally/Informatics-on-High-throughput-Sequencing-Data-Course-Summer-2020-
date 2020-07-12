## Software requirements
<ul>
  <li> Downlod the file <a href="https://drive.google.com/file/d/1xZ5i9Rc0bPgqkb7mqEqj1fWUNf2J6PxL/view?usp=sharing"> <b> centos6_B.ova </b></a> .</li>
  <li> Download the file <a href="https://drive.google.com/file/d/1N56BTgcKwpWlC_NZPfH9Iy6vg3iFTGTj/view?usp=sharing"> <b> centos6_B.ova.md5 </b></a> .</li>
  <li> Download the correct version of <a href="https://www.virtualbox.org/wiki/Downloads"><b> VirtualBox </b></a> according to your operating system. </li>
</ul>

### Notes
<b> centos6_B.ova </b> is a linux-based (i.e. <a href="https://en.wikipedia.org/wiki/CentOS"> <b> Centos 6.6 operating system</b><a>) vitual machine with some installed bioinformatics tools created through Johns Hopkins Genomic Data Science Specialization Courses <a href="https://www.coursera.org/learn/genomic-tools/supplement/OyZzQ/vmbox-download-instructions"> <b> ( Course Name: Command Line Tools for Genomic Data Science)  </b> </a> @ Coursera and all credits go to them. 
  
  ## Setup our Working Environment 
  1. Make sure that you have enough space on your computer, and choose a partition that has at least 3 GB free space to save <b> centos6_B.ova </b> 
  <br>
  <img src="VM_ScreenShots/3.png" class="centerImage"> 
  <br>
  2. Go to your installed Oracle VM VirtualBox and open it. 
  <br>
  <img src="VM_ScreenShots/1.png" class="centerImage"> 
  <br>
  3. Go to File/Import Appliance.
  <br>
  <img src="VM_ScreenShots/2.png" class="centerImage"> 
  or Click on Tools and click on Import.
  <br>
  <img src="VM_ScreenShots/11.png" class="centerImage" width="500" hight="500"> 
  <br>
  4. Choose the location of the file <b> centos6_B.ova </b>. 
  <br>
  <img src="VM_ScreenShots/14.png" class="centerImage" width="600" hight="600">
  <br>
  5. You can change the Machine base folder or Restore Defaults. 
  <br>
  <img src="VM_ScreenShots/15.jpg" class="centerImage" width="600" hight="600"> 
  <br>
  6. Click import. 
  <br>
  <img src="VM_ScreenShots/16.png" class="centerImage" width="600" hight="600"> 
  <br>
  After a sucessful importing of a virtual machine, the following window will appear:
  <br>
  <img src="VM_ScreenShots/17.png" class="centerImage" width="600" hight="600"> 
  <br>
  7. Click on start button. 
  <br>
  <img src="VM_ScreenShots/12.png" class="centerImage" width="600" hight="600">
  <br>
  The following window will appear after starting the linux Centos 6.6 operating system.
  <br>
  <img src="VM_ScreenShots/Screenshot.png" class="centerImage" width="600" hight="600"> 
  <br>
  8. To shutdown the linux machine, choose system/shutdown (do not exit by clicking on x (close) button on the main window).
  <br>
  <img src="VM_ScreenShots/20200712_212402.jpg" class="centerImage" width="600" hight="600"> 
  <br>
  9. To share files among your operating system and the Virtual Machine, put the files on a shared folder and Click on Setting.
  <br>
  <img src="VM_ScreenShots/18..jpg" class="centerImage" width="600" hight="600"> 
  <br>
  10. Select Shared Folders. 
  <br>
  <img src="VM_ScreenShots/19.png" class="centerImage" width="600" hight="600"> 
  <br>
  11. Add the folder that you designed as a shared folder.
  <br>
  <img src="VM_ScreenShots/20.jpg" class="centerImage" width="600" hight="600"> 
  <br>
  12. Select Other and choose your shared folder.
  <br>
  <img src="VM_ScreenShots/21.png" class="centerImage" width="600" hight="600"> 
  <br>
  13. Check on Auto-mount option. 
  <br>
  <img src="VM_ScreenShots/23.jpg" class="centerImage" width="600" hight="600"> 
  <br>
  The following window will appear after a sucessful adding of a shared folder. 
  <img src="VM_ScreenShots/22.jpg" class="centerImage" width="600" hight="600"> 
  <br>
  14. To access the shared folder on the Virtual Machine, open the linux terminal on the Desktop and go to the /media folder by write  <b> <i> cd /media  </i> </b> and hit Enter. 
  <br>
  15. List the folders under the /media by writing <b> <i> ls </i> </b> and you will find your shared folder started with <b> sf_YOUR_SHARED_FOLDER_NAME </b>.
   <br>
  16. Write <b> <i> cd sf_YOUR_SHARED_FOLDER_NAME </i> </b> and hit Enter, Now you can access any files on this shared folder.
  <br/>
  <img src="VM_ScreenShots/Screenshot-1.png" class="centerImage"> 
  
  
  
  
  
  
  
  
 
  
