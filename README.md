# WebOCode                               I have answered all the questions.Please do have a look!!!!

how to run the website locally
2. References which you may have used
3. CSS/JS frameworks
4. How your website justifies the theme you have selected
5. What problems you faced and how you resolved it.
6. What new things you learned by making this website.


Create a new repository on GitHub

1)To begin, sign in to your user account on GitHub.
2)In the upper right corner, click the + sign icon, then choose New repository. This will take you to a page where you can enter a repository name (this tutorial uses test-repo as the repository name), description, and choose to initialize with a README (a good idea!).
3)It is a good idea to add a .gitignore file by selecting one of the languages from the drop down menu, though for this tutorial it will not be necessary.
4)Similarly, in practice you should choose a license to that people know whether and how they can use your code.
5)Once you have entered a repository name and made your selection, select Create repository, and you will be taken to your new repository web page.


Clone your repository to your local machine

Next, clone your newly created repository from GitHub to your local computer. From your repository page on GitHub, click the green button labeled Clone or download, and in the “Clone with HTTPs” section, copy the URL for your repository.

Next, on your local machine, open your bash shell and change your current working directory to the location where you would like to clone your repository. Note that here we are using a bash command - cd (change directory).
Once you have navigated to the directory where you want to put your repository, you can use:
git clone https://github.com/URL-TO-REPO-HERE
The git clone command copies your repository from GitHub to your local computer. Note that this is a git specific command.


Tracking changes with git add and git commit
Edit a file in your repo
Next, open up your favorite text editor and make a few edits to the README.md file. Save your changes.

Once you are happy with your changes and have saved them, go back to your terminal window and type git status and hit return to execute the command.

Add and commit changes
You will use the add and commit functions to add and commit changes that you make to git.

git add: takes a modified file in your working directory and places the modified version in a staging area.
git commit takes everything from the staging area and makes a permanent snapshot of the current state of your repository that is associated with a unique identifier.
These two commands make up the bulk of many workflows that use git for version control.


Commit files
Once you are ready to make a snapshot of the current state of your repository, you can use git commit. The git commit command requires a commit message that describes the snapshot / changes that you made in that commit.

A commit message should outline what changed and why. These messages

help collaborators and your future self understand what was changed and why
allow you and your collaborators to find (and undo if necessary) changes that were previously made.
If you are not committing a lot of changes, you can create a short one line commit message using the -m flag:

git commit -m "Editing the README to try out git add/commit"
Alternatively, if you are committing many changes, or a small number of changes that require explanation, you’ll want to write a detailed multi-line commit message using a text editor.

If you have configured git to use your favorite text editor (via git config --global core.editor your-fav-editor-here), then you can open that editor to write your commit message using the git commit command:

git commit
Once you save your commit message and exit the text editor, the file that you created will contain your commit message.

Push changes to GitHub
So far we have only modified our local copy of the repository. To add the changes to your git repo files on your computer to the version of your repository on GitHub, you need to push them GitHub.

You can push your changes to GitHub with:

git push
You will then be prompted for your GitHub user name and password. After you’ve pushed your commits, visit your repository on GitHub and notice that your changes are reflected there, and also that you have access to the full commit history for your repository!





REFERENCES
tailwind css
some youtube videos
freefrontend website


I used ATOM for writing my code.


I have selected Furniture theme. And i have tried to make a Shopping website for furniture. Because i have heard very less about totally dedicated furniture shopping website,especially in India



Challenge:
I have faced many changes in css.Because i feel html code is not very difficult but CSS is used to beautify it and that what makes it challenging.I have made many try and error,then got the final results.



New things learned:
One major thing i have learned is to make website responsive.I had never done it before.Navigation through different section of the same page and to differnt pages was new to me.

I have done this project with great sincerity and dedication.I have the judges will like it.
