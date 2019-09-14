# Devops Learning Path


### Prerequisite
> **Understanding of Powershell or any other programming language so that you should have understanding about loops and conditions**
>
> *[Click Here for Basic PowerShell Concepts](https://github.com/hclpandv/powershell-training-material)*
>
> *[Click Here for Basic Understanding of Unix Command-line and Github](https://github.com/AgileAshwani/Linux-Basics-commands)*

**Hurray :+1: let's move forward quickly now towards Setting up our Environment :runner:**

### MustHave Stuff to Begin
> :point_right: **Create a GitHub account for Collaboration** *[Try Me](https://github.com/join)*
>
> :point_right: **Install Vagrant** *[Click Here](https://www.vagrantup.com/downloads.html)*
>
> :point_right: **Install Oracle VirtualBox** *[Click Here](https://www.virtualbox.org/wiki/Downloads)*
>
> **Note:** If you wish to use VirtualBox on Windows, you must ensure that Hyper-V is not enabled on Windows. You can turn off the feature by running this Powershell command:
> :point_down:
> ```Powershell
> Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All
> ```
>
> :point_right: **Install WSL [Windows Subsystem Linux]**
>
> Open PowerShell as Administrator and run:
> ```powershell
> Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
> ```
> ```powershell
> Invoke-WebRequest -Uri https://aka.ms/wsl-ubuntu-1804 -OutFile ~/Ubuntu.appx -UseBasicParsing
> ```
> ```powershell
> Add-AppxPackage -Path ~/Ubuntu.appx
> ```
