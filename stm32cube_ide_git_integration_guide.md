# Using Source Control software (Git) in the STM32CubeIDE

Credit: 
- https://www.youtube.com/watch?v=dCE-4dgL82o
- https://www.youtube.com/watch?v=EMME859o5u0

Simply pushing the files from your STM32CubeIDE project to a Git repo seems infeasible, as the instantiated project contains too many files. However, there is an integrated solution.

## Installing EGit

1. Open your STM32CubeIDE
2. Under the "Help" tab at the top of your screen, click "Eclipse Marketplace"
3. In the search bar of the new window, type "egit". The desired plug-in is "EGit - Git Integration for Eclipse 6.7.0" as seen below

<img width="337" height="110" alt="EGit for Eclipse Screenshot" src="https://github.com/user-attachments/assets/7a03e1df-4ab0-46de-b7cd-628db52ce2a4" />

5. Click "Install", then "Confirm". You may see a license pop up; simply accept the terms, and proceed. You may see another window titled "Trust Artifacts". Press "Select All" and then "Trust Selected"
6. You have successfully installed the EGit plug-in, but in order to begin making use, you must restart the IDE. A window should pop-up to prompt you to restart automatically; press "Restart Now"

Once your STM32CubeIDE restarst, EGit will launch with the program successfully.

## Using EGit

In order to leverage Git, we need access to repositories. To find this:

1. Under "Window", select "Show View" and then "Other"
2. You should see a "Git" folder. Clicking on it, you should see "Git repositories"
3. Finally, select that, and you should see a window at the bottom right pop up, as seen below

<img width="347" height="176" alt="Git Window" src="https://github.com/user-attachments/assets/60e5ee8a-f498-4400-aaa2-92098006b3a9" />

From this, there are three options: "Add an existing local Git repository", "Clone a Git repository", and "Create a new local Git repository".

### Add an existing local Git repository
With this, you have 


### Clone a Git repository
With this, you have a **new, empty project locally**, and access to a **remote repository** with which you want to do some work on. This is a two-part process; first, we need to clone the remote repository 
locally, then we must pull the files into the working directory of the STM32CubeIDE.

1. Click on "Clone a Git repository".

### Create a new local Git repository
