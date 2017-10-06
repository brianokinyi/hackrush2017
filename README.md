# hackrush2017
What is Git and Why you should use it
GIT
github.com

INTRODUCTION
Git is a software that is used for Version Control. It is free and open source.
Version Control is the management of changes to documents, computer programs, large websites and other collection of information.


WHY YOU SHOULD USE GIT
You have access to all versions of all files in Git repository at any time, it’s almost impossible to lose any part of a code.
Multiple developers can work on one project at the same time without interfering with each other, and without fear of losing any changes made by a colleague.
Large developers community and online websites to upload your source codes or get others source codes to make your work easier
Lots of software available for both who comfortable with command line and for others GUI tools
Easy and clear documentation to get started with
Git doesn’t need much bandwidth. Only connect when done


GIT BASH

Basis operations are:
Initialize
Add
Commit
Pull
Push

ADVANCED OPERATIONS
Branching
Merging
Rebasing


Initialize
	Creates an empty Git repository 
	Command: 
		$ git init

Add
	This command will add all the files to the index which are in the 	directory
	Command: 
		$ git add <filename>


Commit changes
	Record changes to the repository
	Command: 
		$ git commit –m “<Message>”

Push
	This command transfers commits from your local repository to 	your remote repository(online in GitHub). 
	Command: 
		$ git remote add origin “https://github.com/username/repo.git” 
		$git push –u origin master

Pull code
	Fetches changes from a remote repository to a local repository


