# bento

This is an attempt as a faster, easier-to-setup version of [pwnvm](https://github.com/OpenToAllCTF/pwnvm), **with PowerShell scripts**.

## Installation
### Windows (Without WSL)
1. Install Docker: [Using chocolatey](https://stefanscherer.github.io/get-started-with-docker-on-windows-using-chocolatey/) is the most convenient way for me 
2. Run PowerShell as administrator and make sure `ExecutionPolicy` is set to `Unrestricted` or `Bypass` (run `Set-ExecutionPolicy Unrestricted`)
3. Build: `./build.ps1`

### Windows (With WSL)
Docker has support for WSL now. Download the installer, follow the installation instructions, and run docker commands in WSL.

### MacOS
Use installer.

### Linux
https://docs.docker.com/engine/install/#server

## Running it
* Pull - `./pull` or `./pull.ps1`
* Start - `./start` or `./start.ps1`
* Connect - `./connect` or `./connect.ps1`
* Stop - `./stop` or `./stop.ps1`
* Build (not required if pulled) - `./build` or `./build.ps1`

## Credits
https://github.com/Grazfather/pwndock
