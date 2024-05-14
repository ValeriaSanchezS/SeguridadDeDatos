# Apple MacOS

### Run the following command to verify there are NO software updates:

 /usr/bin/sudo /usr/sbin/softwareupdate -l 

"Software Update Tool"
"Finding available software"
"No new software available"

### Run the following command to verify what packages need to be installed:

/usr/bin/sudo /usr/sbin/softwareupdate -l

The output will include the following:

"Software Update found the following new or updated software: "

### Run the following command to install all the packages that need to be updated: To install all updates run the command:

/usr/bin/sudo /usr/sbin/softwareupdate -i -a

#Or run the following command to install individual packages:

 /usr/bin/sudo /usr/sbin/softwareupdate -i '<package name>'

