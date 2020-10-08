# Git

Some Global Configuration for Git
Open a cmd window or terminal on your computer.

Check to make sure that Git is installed and available on the command line, by typing the following at the command prompt:
git --version

To configure your user name to be used by Git, type the following at the prompt:
git config --global user.name "Your Name"


To configure your email to be used by Git, type the following at the prompt:
git config --global user.email <your email address>


You can check your default Git global configuration, you can type the following at the prompt:
git config --list




Set the local Git repository to set its remote origin
At the prompt, type the following to set up your local repository to link to your online Git repository:
git remote add origin <repository URL>



Pushing your commits to the online repository
At the prompt, type the following to push the commits to the online repository:
git push -u origin master



Cloning an online repository
To clone an online repository to your computer, type the following at the prompt:
git clone <repository URL>
