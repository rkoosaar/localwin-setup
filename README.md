# Configuration and setup of my local windows machines

The plan is to collect automation scripts and configurations for setting up my local windows machines here. If someone else finds it useful, then its fair picking and happy to get feedback and ideas from community on how to do it better. I dont have everything automated yet.
Its an experimentation corner of how to automate local machine setup.

# The cornerstone are these technologies

- Chocolatey
- Powershell and Powershell Core 

# How to run it?

1. Create your own config.ps1 to define the choco packages, npm packages, zip downloads, etc that you want to configure.
2. Run as Admin in powershell `Setup-Machine.ps1 -ConfigFilePath .\ConfigFileNameHere.ps1`