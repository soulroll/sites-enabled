# Sites enabled config file

An example apache2 project config file for setting up development websites on Linux creating a symbolic link to files.

## Installation
1. Place or copy this file into your /etc/apache2/sites-enabled/ directory using sudo.
2. Change the user and project link details within the file to your desired location and address.
3. Add the link to the etc hosts file for local development (project.user.co.nz 127.0.1.1).
4. Run: sudo service apache2 restart.
