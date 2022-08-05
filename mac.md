## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
   A: Git is essentially a version control system using a useful minimum set of commands.

2. What is the difference between Git and GitHub?
   A: Github is the version control system, whereas GitHub is essentially a cloud storage container for the Git Repos that developers make to store their projects in.

3. Why do we create a branch?
   A: Branches are created for multiple reasons, but most common is to be able to write code for a feature without breaking the code on the main branch.

4. What is the purpose of a Pull Request?
   A: The main purpose is to be able to compare the code written with the code already on the branch that is being compared to. It is to help us not introduce new bugs into a project.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
   A: You would use the git branch followed by the branch name. ie. git branch main.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
   A1: git fetch: Basically, this is used to get the newer code ONLY. It will not manipulate any code, so it is good to be able to see if there is anything new.
   A2: git merge: This is the command line's way of basically merge two branches together.
   A3: git pull: This one is used to fully update where you are at to where the most recently updated code is that has been merged.
7. What is a merge conflict?
   A: A merge conflict is where two branches will contradict and break one another. It is helpful because then you can work on making the necessary changes to be sure something will not break.
8. How do you resolve a merge conflict?
   A: Honestly, the only way to do this is to either remove the code from the pull request altogether or keep writing code that will help the two branches integrate with one another.
