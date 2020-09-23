# NoPE
 Node PowerShell Web Server using Express. Should you do this, NoPE, hence the name. This is verry much under development and should not be used in any production environment. 

# Installation
### Requirements
 - Microsoft Windows 10, Server
 - PowerShell Enabled 

### Fulfill Dependencies
Basic installation. Just navigate to the directory and run

``npm install``

### Configuration
Edit 'config.json' to configure application settings.

### Service Installation
Install SSL Windows service with

``node ServiceInstall-SSL.js``

Install NON-SSL Windows Service with

``node ServiceInstall.js``

Self Signed Certificates are included, but replace in production, better yet, don't use this in production. NoPE.

