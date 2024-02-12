# The shell script for the installation of Tomcat Server on Ubuntu/Debian

# Run the below commands step-wise one-by-one to install the Tomcat Server

  # 1. Change dir to /home
    cd /home
  
  # 2. Download the tomcat-install.sh
    sudo wget https://raw.githubusercontent.com/prabhatraghav/tomcat-install/main/tomcat-install.sh

  The Tomcat-install script is set to install Tomcat Version 10.0.18 (on port 8080) with Java version 17 as a default settings. But, you can make the necessary changes as per your requirements. To make changes to the main script, edit the "tomcat-install.sh" file and set the desired tomcat install environment elements like (TOMCAT_VERSION, TOMCAT_USER_PASS, TOMCAT_MANAGER_PASS, CUSTOM_TOMCAT_PORT, CUSTOM_JDK_VERSION etc.) and save the file before the run.
  
  # Edit the script (Skip this step if you want to install with default settings)
    sudo nano tomcat-install.sh

  # 3. Make it executable
    sudo chmod +x tomcat-install.sh

  # 4. Run the script
    sudo sh tomcat-install.sh

# Please read the instructions carefully, echoed on the screen at the end of this script, and save the tomcat-user and manager passwords.

# 5. Use the command to start the Tomcat
    tomcat-up

# 6. Use the command to stop the Tomcat
    tomcat-down

  
This script is developed by PRABHAT RAGHAV prabhat_raghav@outlook.com
(https://github.com/prabhatraghav/tomcat-install)
