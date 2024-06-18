## Setting Up The Environments of different Packages on Windows

### Python Environnment set up on Windows
1. download Python package - Visit the official Python website (https://www.python.org/) and download the latest version of Python for your operating system.
2. Install python - Access python package on downloads and install, make sure to select the option to add Python to the system's PATH environment variable.
3. open terminal and run ``` python --version ``` to confirm python has been installed.

### Install Dart Environment
1. Go To https://dart.dev/get-dart
2. Select the recommended version for your operating system
3. Install chocolatey if it hasn't been installed on your pc. Install using the command below
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
4. Launch PowerShell
5. Then install dart ``` choco install dart-sdk ```
6. run ``` dart --version ``` to confirm dart has successfully installed
7. if getting error, Locate and Copy the path of dart bin folder
8. open the system Environment Variable and the path of the bin directory to User Variable.

### Install mysql
1. Go to https://phoenixnap.com/kb/install-mysql-on-windows.
2. Download the recomended version for your pc.
3. Follow Instruction the official mysql documetation to configure product according to your needs. 