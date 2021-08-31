## Lab 1: Submitting Homework on GitHub

We will first practice how to pull, work on and submit your homework on github. We have set up a  homework #1 repo for you. Go to the [datasciencelabs-student github page](https://github.com/datasciencelabs-students) and look for a repository named `<your GitHub username>-2020HW1`. Click on the repository and follow the next steps below.


1. Copy the link near the top of the page that is revealed after clicking 'clone or download'.

 <center><img src="./images/git-clone.png" alt="gitclean" style="width: 600px;"/></center>

2. In RStudio, start a new project: 

> File > New Project > Version Control > Git

<center><img src="./images/newproject.png" alt="gitclean" style="width: 600px;"/></center>

In the "repository URL" paste the URL of the homework repository you just copied. Take charge of – or at least notice! – the local directory for the Project. A common rookie mistake is to have no idea where you are saving files or what your working directory is. Pay attention. Be intentional. Personally, I suggest you check “Open in new session” and to keep all your homework repositories in a 'BST260' folder.

<center><img src="./images/directorysetup.png" alt="gitclean" style="width: 600px;"/></center>

3. Click "Create Project". You should now see the files in the repository in the lower right window in RStudio. Also notice the Git tab in the upper right window.

 <center><img src="./images/rstudio_screen.png" alt="gitclean" style="width: 700px;"/></center>


### Working on your homework

Once you have a local copy of your repository, it's time to get to work! 

Using code presented in class, answer the first question. When you are finished, `knit` the file. 

You have updated the file on your personal machine, but not the file on your github repository. To do this, click the `commit` button in the Git tab window. This is equivalent to `save` in most programs. But what is special about `git` and other version control software is that we can track 
and revert changes!

Now write a `commit message`, which will help you keep track of the changes we made when you look at this in the future. Leave detailed messages so that future you will know what you did. Future you will thank you.

 <center><img src="./images/rstudio_commit.png" alt="gitclean" style="width: 700px;"/></center>

You can now `push` your work to Github by clicking the *green up-arrow* in the Git tab window. If you are asked for username and password, provide them. Note, you can (and should) do this as many times as you want before the homework deadline. What is great about this is that it will make getting help from your TA easier as well as keeping a copy of your work in the cloud in case your computer crashes, or you accidentally delete something.	Also note that committing your work without pushing it will not update the file in your repository. So always remember to push!

To check that the push was successful, refresh your github repo page, click on your homework file and see if the file was updated. You can also look at the `last commit` column to see when your files were last updated.

### Summary
To summarize, it is important to do the following 
steps whenever you finish working on your homework to make full 
use of `git` and Github as well as generally having the best 
experience in this class. 

1. Work on your homework
2. Commit changes to your local repository: `commit` button in Git tab in RStudio
3. Push the changes to your github repo: `push` (green arrow) button in Git tab in RStudio

Generally keep this picture in mind whenever you want to do this 
loop, it is important to only add changed files you care about 
and nothing you do not care about. If certain files keep popping 
up in your git status that you will never want to add, e.g. `.Rhistory`, 
etc, add them to your `.gitignore` to simplify your life, this will keep 
those files from showing up here. For more info on this see the 
`version_control.Rmd`

![add](./images/git_add.png)

![commit](./images/git_commit.png)

![push](./images/git_push.png)


