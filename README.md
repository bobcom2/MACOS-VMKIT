# MACOS-VMKIT
I want to provide a simple test environment for those who cant get the hardware

# Requirements

* [VMware Workstation Pro](https://support.broadcom.com/group/ecx/productdownloads?subfamily=VMware%20Workstation%20Pro&freeDownloads=true)
	* This is good for Windows and Linux
 	* You will need to create a Broadcom Account
  	* Plus it's Free for Personal Use

* [Unlocker for Vmware Player and Workstation Pro](https://github.com/BDisp/unlocker)
    * This will be the **Most Important** Requirement throughout this whole ReadMe. Without it, You're bootlooping
    * **note** You must re-unlock after updating Workstation Pro
      
* [VM Templates](https://drive.google.com/drive/folders/1DIvjPQzIfyzy0Mj8hEq0Kz1kItAOofXt?usp=drive_link)
	* This will be hosted on Google Drive.
 	* This will include two Variants.
   
	# Hardware Requirements
  * At least 100 GB or free space
  * RAM 
  	* Minimum: 4Gb
  	* Recommended: 8 GB or more
   * I do recomend an NVME or SSD Drive
   	* During my testing, I noticed the significant perfomance drop while running it on a HDD 

# Instructions

1. Determine Your OS
	* Is it Windows or Linux?
2. Create your boadcom account if you havve already, you can skip this step
	* Click the login button on the top right of the page
 	* register
  	* insert your email (it can be personal)
   	* follow the prompts
   * Reopen the link again
   * select either Windows or Linux
	* If Linux
 		* the file will be a .bundle, which must be run as an executable.
 		* Run as **sudo** or **root**, i reccomend **su**.
   	* If Windows
   		* the will be a standard .exe file
3. Install
	* Windows, open the file and follow the prompts
 	* be sure to select run for personal use.
4. Install the unlocker
5. Open Wmware Workstaiton Pro
6. Import the Template/OVF file
	* This will create a copy from the template provided
7. Click Run and your set 
