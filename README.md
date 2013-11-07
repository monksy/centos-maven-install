centos-maven-install
====================

This is a script that automates the download and installation of the latest maven 

This was made with help from http://xmodulo.com/2012/05/how-to-install-maven-on-centos.html

How to run:

chmod +x maven-install.sh
sudo ./maven-install.sh

TODO: 
  - Check to see if the user has permission to write to /usr/local
  - Check to see if the mvn command exists after fixing the environment variables
  - Better error messages
  - Check for a previous installation
   - If found prompt for removal
  - Argument to install a specific version
  - Detect the current version with regex 
  - Download to a temporary directory
  - Verify instalation
  - Handle all of the sudo access within the script
  - Handle mirrors
  - Fix the installing user's path and m2 variable after the install

Author assumes no responsiblity or liablity for this script, use at your own risk and ofcourse read/understand what this does before running.
