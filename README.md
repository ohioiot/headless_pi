## Headless Pi setup for Git Bash users on Windows
#### This same process could be implemented with any OS and shell of choice, but that's beyond the scope..
#### check out this video for visual steps on how to implement this code


### In this repo:

There are three files in this repository:

Copy the lines in **aliases** ~/.bash_profile file.  These commands provide a shortcut to the scripts you actually want to run.

mv **headless.sh** and **clear.sh** to any directory you choose to store your scripts.

go ahead and delete the repo - I don't think you'll be needing it after this.

### update the path in our repo:

I prefer to work out of a */workshops* subdirectory of my home directory, so the path to my scripts is */c/Users/Larry/workshops/scripts*
  
So, my aliases in *~/.bash_profile* should read:

    alias headless='/c/Users/Larry/workshops/scripts/headless.sh'
    alias clear='/c/Users/Larry/workshops/scripts/clear.sh'

Update yours accordingly.

~/.bash_profile only runs when you open the shell.  So, to see these changes, either open a new shell, or type ```source ~/.bash_profile``` in your shell to load the new info.




