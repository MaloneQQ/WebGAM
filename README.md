# WebGAM
An open source web frontend for GAM (Google Apps Manager).  The goal is to create a cleaner &amp; more functional web based interface for managing your Google Apps domain than what is available using only Google's Admin Console.

This project is still in the beta stages & may not yet be suitable for managing your production Google Apps domains.  Read the documentation & test in a suitable environment prior to use in your production domains.

# Limitations
WebGAM has many limitations right now.  It is currently only known to work on Ubuntu Server 14.04.3 LTS 64-bit but may work on other Debian-based distros as well.  Only basic functionality for managing Google Apps domains is currently available in WebGAM.  See the documentation for a list of current capabilities & planned features.

# Requirements
- A paid Google Apps account.  This software does not work with a free Google account.
- GAM (Google Apps Manager) installation.  The WebGAM installer will automatically install GAM if not already present on your system.
- The WebGAM installer will install Apache, PHP & other prequisite packages if they are missing on your system.  Please see the documentation for details on what is installed & how to run the installer.
