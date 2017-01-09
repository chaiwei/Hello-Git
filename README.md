# Hello-Git
A Beginner's Git and GitHub Tutorial

## Introduction
Git is a command line tool use for Version Control (or Revision Control) that lets you track your files modification history over time.

GitHub.com is a code hosting platform for version control and team collaboration. It lets you and others work together on projects from anywhere.

### Step 1. Create a new Repository
Clone an existing repository

    git clone https://github.com/username/reponame.git

or

Create a new repository

    git init

### Step 2. Make changes
Create a file and type something and save.

Add all current changes files to next commit

    git add .

### Step 3. Commit Changes

    git commit -m "Initial commit"

### Step 4. Push commit to origin (Github)

    git push origin master


## View changed file in working directory

    git status

## View changes to tracked file

    git diff
