# packages_vscode
external packages for vs code that I am used for coding in angular & typescript projects

## create a batch file on the source mashine

go on cmd promt and type:

> for /F "tokens=*" %i in ('code --list-extensions') do @echo call code --install-extension %i >> install.cmd

this will create a batch file named install.cmd

copy this batch file to the destination mashine an run it in cmd console


### In this repo you can find my actually used add ons for vs code in Angular projects.
