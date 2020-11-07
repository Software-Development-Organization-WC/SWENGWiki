# Your first commit

### After creating the new remote repository, if you are creating a new local repository,  open git and use the Command Line Interface to navigate to the directory of the files which you want to put into the remote repository on Github. You can make a simple text doc in the directory to illustrage how commits work. Lets assume you have a README.md in the directory.  <br/>Type:

>***git init***
><br/>(this initializes a .git folder and git files in the current directory)<br/><br>
>***git add README.md***
><br/>(this adds the README.md document we put in the directory to the git staging >area. It tells Git that you want to include this file in the next commit.)<br/><br>
>***git commit -m "First Commit"***
><br/>(***-m*** means message, and the message is located between the two quotation marks)<br/><br>
>***git remote add origin https://github.com/YourGithubUsernameHere/YourRepoNameHere.git***
><br/>(this adds the remote origin for your local files and local git directory)<br><br>
>***git push -u origin master***
><br/>(this pushes your local changes to the remote repository located on github.com)<br/><br>

Now you can go to your repository on Github and see your README.md located in your remote repository! You can see an example below:

![ExampleFirstCommit](../../resources/images/git/firstCommit.png)

---

### If you want to ***push an existing repository*** from the command line, type the last two previously listed commands:

>***git remote add origin https://github.com/YourGithubUsernameHere/YourRepoNameHere.git***<br/><br>
>***git push -u origin master***
