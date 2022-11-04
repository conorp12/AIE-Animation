# AIE-Animation
Tutorial for using manim to make AIE presentation animations

# Setup  
I followed the tutorial found [here](https://docs.manim.community/en/stable/installation.html).  
For a windows machine it is easiest to install a packet manager like [chocolately](https://chocolatey.org/install) via the powershell in admin mode.  
From here enter;
```.sh
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
When Choclately is installed, in power shell enter the following commands to download Manim and Latex (which is required for Manim)
```sh
choco install manimce
```
```sh
choco install manim-latex
```
Now you should be setup and able to follow the tutorial found [here](https://docs.manim.community/en/stable/tutorials/quickstart.html) to get started.
