# Boxstarter_Windows10_Development
A simple script to set up a windows 10 development environment in a consistant way

Run the boxstarter web powershell installer script

```
. { iwr -useb http://boxstarter.org/bootstrapper.ps1 } | iex; get-boxstarter -Force
```

Install this repository via boxstarter

```
Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/mallek/Boxstarter_Windows10_Development/master/Boxstarter-Base.txt -DisableReboots
```

For a development install run this, this does a lot more tweaks to the OS and installs some everyday developer tools
```
Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/mallek/Boxstarter_Windows10_Development/master/Development.txt
```
