# Ted, an easy rich text processor
 
Ted for Linux: copyright and disclaimer
How to install Ted
Compiling Ted from source
Author
 
 
1)
Ted for Linux: copyright and disclaimer
Ted is free software. By making Ted freely available, I want to contribute to the propagation of Linux as a viable platform for technical computer enthusiasts. As Ted is free software, I assume no responsibility for the consequences of using it. It is up to you to decide whether Ted suits your purpose or not. Ted is distributed with absolutely no warranty under the terms of the GNU Public License.
 
2)
How to install Ted
The installation of Ted depends on the platform and on the kind of distribution. Binary distributions for Intel ix86 Linux are available from the download site http://ftp.nluug.nl/pub/editors/ted. The distribution comes in the form of compressed tar archives and as Red Hat package manager (RPM) packages and Debian installer packages (DEB). Binary distributions for other platforms might be available. For more or more recent information refer to the Ted web site http://www.nllgg.nl/Ted. All binary installer .tar.gz packages are packaged relative to /.
 
To install Ted or one of the localization packages from an RPM package, log in as root, (Or any system user with sufficient permissions to install packages.) and give the command rpm -i <package-details>.rpm . To upgrade from a previous version of Ted give the command rpm -U <package-details>.rpm. The corresponding command on Debian based Linux versions like Ubuntu is dpkg -i <package-details>.deb. It takes care of installing as well as of upgrading. I used Ubuntu 12.04 to build the *.deb and *.tar.gz files and fedora 17 to build the *.rpm files. A Solaris build can be installed with pkgadd -d <package-details>.pkg.
 
To compile Ted from source. Refer to the compilation instructions at the end of this document.
 
Overview of the different packages:

# This repository is made so new users can install Ted. No copyright infringement is needed. This repo places all the dependencies and Ted's Deb files that can be used to install it on latest Debian and Ubuntu systems. Find everythign in the releases.
