# The RootHacks Git Practice Zone

The repository for new hackers to learn and practice git cloning, branching, committing, pushing, pulling, and merging.

This repository is a way for you to practice using GitHub in an environment that is similar to what you will be doing in a hackathon.  

After finishing the exercise here, you'll understand the basics of using git in the command line and will have an idea of how to use git with your hackathon project.

This exercise won’t go into how git works and its full terminology, there are plenty of online resources for that such as 
- [the `git` book](https://git-scm.com/book/en/v2)
- [Learn X in Y Minute's git guide](https://learnxinyminutes.com/docs/git/)

You’ll may want to have a rough idea of the following before getting started
-   Version control
-   Commits    
-   Branches
-   Remote vs local branches

Keep in mind the IDE of your choice likely has nice UI versions of git that may be easier to understand and use when actually hacking, feel free to use those for this exercise as well, but in the end those are also just sending git command line commands. So if you learn it with the command line it will be easy to understand what's going on with the UI.

Finally, if you have any questions, ask your questions in `#git-sandbox` on the RootHacks Discord! We specifically designed this exercise to be done on your own time so that if you ever get stuck you can ask questions or do some searching around before 

# Getting Started
1.  Install Git 
	a.  the process will vary depending on your operating system, doing a search of “Install git [your operating system here]”   
	b.  You’ll know it’s done when you type `git --version` and it tells you your git version and doesn’t give an error
2.  Open your terminal and navigate to somewhere you want to put all the git files for this exercise. 
	a. In your terminal, you can navigate with `cd <address to the folder>`
3.  Clone this repository with `git clone https://github.com/JoshuaJLi/RootHacksGitPracticeZone.git`
4.  Navigate to the repository folder with `cd RootHacksGitPracticeZone`
5.  DM me (Jugblue#2169) your github username/email so I can add you to the repository so you can make your changes and see them on here.
    
# Super Git Basics
6.  Create a branch using `git checkout -b <name-of-your-branch>`, it can just be your git username, note no space are allowed, so use your favourite space delineation technique
	a. This branch name will be visible to everyone is the repository so don’t name it your SSIN or anything else you don't want everyone to see
7.  In the folder, create a .txt file in the git folder and write a message in it, also feel free to edit the basic `helloworld.py` and `helloworld.html` files.
8.  Once you have completed your changes, go back in your git terminal, use `git add <names of the files you edited/created here>`
9.  Create a commit with your newly added files with `git commit -m “<A descriptor of what you changed here>”`
10.  Push your local commit to remote  with git push
    
Congratulations! If you did everything correctly, you should be able to see your branch on https://github.com/JoshuaJLi/RootHacksGitPracticeZone and see the file you added to it. 

11. Go to the pull requests tab in this GitHub Repository and select "Create Pull Request"
12. Select your branch
13. Hit "Create Pull Request"
14. GitHub will make notes of any merge conflicts (in the situation where you edited a line that someone else edited)
  a. You can fix them manually, or your favourite IDE has tools that can make the process easier
15. Once there are no conflicts, you can create a merge request, and then approve the merge request
16. Congrats! The code you made is now on the main branch! And the changes you made didn't interfere with anyone else's development. 

# Other Resources
- Check out [this git visualization tool that shows you what happens when you branch, commit, and push](https://git-school.github.io/visualizing-git/#free-remote)
