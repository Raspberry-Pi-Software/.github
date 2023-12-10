# Welcome to Raspberry Pi ©️ Software.
Welcome to Raspberry Pi ©️ Software, a organization filled with repositories for use on the Raspberry Pi ©️!

# Supported/tested models of Raspberries
- Raspberry Pi ©️ 4
  - 64-bit
  - 32-bit (in progress)
- Raspberry Pi ©️ 400
  - 64-bit
  - 32-bit (in progress)
- 2011, 256 MB of RAM Raspberry Pi ©️
  - Not tested yet, incompatible with most repos.

# Install our repositories on your system at anytime (for future and present use)
Install our packages tool using this command:
```bash
git clone https://github.com/Raspberry-Pi-Software/packages-tool && cd packages-tool && sudo bash install;
```
We will install the packages tool to these directories:
```
|- /
|-- /bin
```
The packages tool can then be uninstalled using this command:
```bash
cd packages-tool && sudo bash uninstall;
```
Install packages after install using this command:
```bash
rpisft install <package>
```
<package> would be the GitHub repository name.

To install or uninstall the package tool, to install and remove packages you will need to have an internet connection on your Pi.
