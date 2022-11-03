# hackpkg
The convenient cross distribution package manager for penetration testing utilities

# Intro
HackPkg is a Python3 based penetration testing package manager for quickly, effortlessly, and properly managing packages on your system. Whether you are running a low resource environment or high paranoia environment this package manager solves some issues for you. Setting up virtual machines works, but you're usually doing it because the operating system comes loaded with penetration testing tools which usually requires long wait times for downloads and a laggy system on low resource machines. Many of these tools are installed on your system via the package manager restricting you to a single linux distribution (Debian). By using HackPkg as an alternative, we are not suggesting you replace any virtual machines or currently existing precautionary measures. Instead, you are free to use whichever distributions you wish on your host and virtualized systems assuming they are able to run necessary build dependencies.

HackPkg works differently than other package managers. While other packages managers like yum, dnf, apt, etc download and install pre-built binaries onto your system, HackPkg installs source code build scripts onto your system. 
