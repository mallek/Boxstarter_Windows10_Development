# Boxstarter_Windows10_Development
A simple script to set up a windows 10 development environment in a consistant way

Run the boxstarter web powershell installer script

```
. { iwr -useb http://boxstarter.org/bootstrapper.ps1 } | iex; get-boxstarter -Force
```

Install this repository via boxstarter

```
Install-BoxstarterPackage -PackgeName https://gist.githubusercontent.com/Boxstarter-Base.txt -DisableReboots
```
