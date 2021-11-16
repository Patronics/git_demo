# git_demo
This is a Git Repository set up to allow other robotics club members to get started with Git

If you're running macOS or Linux then git is likely already installed, but if you're running windows you'll need to follow [these instructions](windows.md) to install Git for Windows

[here's a page with a good tutorial for starting to use Git and Github](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners).


### cloning
To clone this repository simply create a new folder (with the ```mkdir``` command or use the GUI), 
change to this directory with ```cd path/to/your/new/folder``` (or just ```cd folder``` if you're already in the parent directory),
and use the command ```git clone https://github.com/Patronics/git_demo.git```

you will now have an exact copy of the repository you cloned
you can work with files in the new folder just as you normally would.

### staging changes
When you're ready to save your changes and submit them back to the repository, there are a couple steps to go through

First you need to add any files you've changed and want to submit to the "staging area".

use the command **git add filename.ext** (you can run **git status** at any time to see what files have changed that you may want to add.

### committing

when you've staged all the files you want, you then use ```git commit -m "description of what's changed"``` to officially record your changes and add to the version history.
You typically want to commit (and stage first) any time you've made any significant changes, and whenever you're at a point that the code works sucessfully.

### pushing changes

there is one last step to share your changes with everyone else, pushing them. 

If you haven't already created a GitHub account, now's the time to do so
once that's done, tell me your username or email you used for the account, and Ill add you as a collaborator. This only needs to happen the first time you push a commit.

when that setup is complete, you can simply use the ```git push``` command to push all new commits to the shared repository, so those changes will be available to everyone.
