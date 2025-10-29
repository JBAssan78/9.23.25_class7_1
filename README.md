# GitHub Repo Setup

This will be a step by step guide on how to set up and use github, using gitbash for command line control. As well as connecting gitbash and github to laptop and VS code Visual Studio Code.

GitHub is a web-based platform built on the Git version control system that allows developers to collaborate on code and manage projects

**Must Know Commands**

CD: Change Directory

MKDIR: Make Directory

LS: List

Touch: New Empty File

**Git Commands**

git init: Initializing a new, empty repository

git add README.md: read me file

git commit -m "first commit":  save staged changes

git branch -M main: master branch made

git remote add origin: connection to github repo to gitbash

git push -u origin main: turns master to main branch

 ## Step 1
**Creating and Managing a Folder in Git Bash**

The first step is to open your Git Bash command line and navigate to (or create) a working directory. Use the cd command to move into your desired folder. For example, let’s create and work inside a folder called TheoWAF1:

cd /path/to/your/directory
mkdir TheoWAF1
cd TheoWAF1

Once inside the folder, you can add new files using the touch command. For instance, to create two files named notes.txt and sandbox.txt, run:

touch notes.txt sandbox.txt

To confirm that the files were created successfully, type:

ls

You should now see both notes.txt and sandbox.txt listed in your folder.

