# ProjectCyber

## Pre-requisites
- Unity Engine 4.25.1
- A command line / terminal prompt capable of running the `git` command (i.e. Git Bash https://gitforwindows.org/) 

## Setup
- Download and install the Git LFS extension from https://git-lfs.github.com/ which adds support for large binary files
- Using a terminal that supports Git, navigate to the folder where you want your project folder to be created
- Use `git lfs clone https://github.com/IndecisionGames/ProjectCyber.git` to clone the project
- cd into `ProjectCyber` and run `git lfs install` 
- Open the `ProjectCyber` folder in Explorer then right click `ARPG_Platformer.uproject` and click `Generate Visual Studio Project files`
- Open Unreal Engine; in the projects tab click `Browse` at the bottom and navigate to and select `ARPG_Platformer.uproject`. When prompted to rebuild modules, click `Yes`.