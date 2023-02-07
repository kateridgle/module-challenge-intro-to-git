## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
    Git is a version control system. But also it's a software program used to navigate, edit, add or troubleshoot files in your OS through a terminal mainly used by programmers.

2. What is the difference between Git and GitHub?
    Git is the program while Github is the site used to store and share code/repositories to other programmers.

3. Why do we create a branch?
    We create branches so that multiple programmers can work off a main source of code at the same time.

4. What is the purpose of a Pull Request?
    It allows our code to be reviewed by a lead or fellow programmer before being added to the main branch.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
    If you want to switch to the main branch you type "git branch -M main". If you want to create a new branch it's "git checkout -b 'your-name'".

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    git fetch is when you add changes to a remote repository WITHOUT commiting them unlike git pull. With fetching the review of code happens before the commit while in a pull it happens after. A git merge is taking a reviewed and changed or added code and merging it into the new main code. Merges can only be done through a git pull request.

7. What is a merge conflict?
    A merge conflict is when a commit is pushed from 2 sources that affect the same line of code and git needs help resolving the issue.

8. How do you resolve a merge conflict?
    Open gitbash and navigate to the repository that has the merge conflict and list the files that are affected. Open them in visual studio code and look for the "<<<<<<<<==========>>>>>>>>" which will divide the changes causing the conflict. At this point you decide which to keep or add the changes together, delete the markers and finally add your changes. Commit. And Push.


