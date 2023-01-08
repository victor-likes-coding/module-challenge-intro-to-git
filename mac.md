## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a version control system that allows for effortless collaboration remotely.
2. What is the difference between Git and GitHub?
Git is the version control system that keeps tracks of changes to a repository. Github is a website that hosts code repositories. They are not the same.
3. Why do we create a branch?
It allows us to work on different features so we're not all working on the same branch that could lead to conflicts when saving changes. It can still happen of course, but it helps us bring our changes into the main/master branch after thoroughly reviewed by pushing and creating pull requests.
4. What is the purpose of a Pull Request?
It allows us to merge our changes into different branches, like the main branch after being approved by a code reviewer.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
`git checkout main`
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch - pulls without merging into the current branch
git merge - takes code from one branch and merges it into the branch you're currently on
git pull - git pull is shorthand for git fetch followed by git merge FETCH_HEAD
7. What is a merge conflict?
A merge conflict is where changes are made to the same area in the code which results in 2 variants and code from one branch needs to be chosen instead of the other to resolve the discrepancy.
8. How do you resolve a merge conflict?
Choose which version of the code from both branches to keep and commmit it after deleting the other conflicting code.
