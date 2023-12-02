# GitHub
Hello Welcome in the world of Git and GitHub

# Section 1 : Welcome to Git

## Course Content
| Unit 1 | Unit 2 |
|--------------|------------|
| Version Control System | Merging|
| Command Line Tool | Rebasing |
| Git Intro | GitHub Intro |
|Tracking a project | Social Coding with GitHub|
| Git additional Cmd | Rewriting History |
| Branching | |

|                       |
|-----------------------|
|  **Create a Portfolio** |

## Learning
- 1. Appreciate the purpose of VCS
  2. Project Management
  3. Create & host your own website
  4. Contribute to Opensource
 

# Section 2 : Version Control System

## Web portfolio
- index.html -> about.html

## Version Control System
- Version Control is a <ins>**manager software**</ins> responsible for **managing chnages** to the computer programs, doc, websites & other collection of info.
- Easy recovery of files/folders
- Rollback to the previous versions
- Informs about who, what, when, why changes have been made

## History of VCS - Evolution
1. **Local VCS**
   - Changes are stored in a database, along with timestamp
   - Code in local system
   - Cons -> Project can be lost, if your hard-disk is corrupted
     
2. **Centralize VCS**
   - **Repository** -> A directory(folder) where your files reside
   - Repository can be a local folder in your PC or a remote folder on a server
   - There are 2 types of repository :-
     1. Local Repository
     2. Central Repository
    
   - Centralized VCS contain just one repository i.e Central repository and each user can access it to work
   - Cons -> Server goes down then nobody can work + if server hard-disk corrupt

3. **Distributed VCS**
   - Contains multiple repositories, each users has their own local repository & there is a central repository where the final code resides
   - push & pull to/from central repository by each users
   - provide full back-up of the project, all users will have full project
   - eg: Git is an example of distributed vcs
   - n local repositories --push-->.....<--pull-- 1 server repository
   - Everyone uses this Distributed VCS
  
## How is Git created?
- In 2005, by Linus Torvalds (creator of Linux Kernel on which many OS created like ubuntu,kali linex etc)

## What is Git?
- **free and open source** distributed VCS designed to handle everything from mini to macro projects ***with speed & efficiency***
- Stores snapshot of your project (not differences)

## Why Git & its Features
- Why Git -> **{ 1.Collaboration, 2.Storing Versions, 3.Analyse Code Changes }**
- Features -> **{ 1.Distributed, 2.Everything is Locally, 3.Non-linear/Branching, 4.Secure/Integrity(Hashing), 5.Speed(C) }**


# Section 3 : Setting Up Environment

## Installing Git
- [**git-scm.com**](https://git-scm.com/)
- Download cmd line version -> check from your command prompt git --version
- Git Bash is terminal in linux, here act as simulator to run linux cmd on Windows OS

## Configure Git
- Who are you? bcuz you're going to be a user of Distributed repository So create your identity
- git config --global user.name "User_name"
- git config --global user.email "User_email"


# Section 4 : Command Line Tool
| GUI   |    CLT|
|-------|-------|
|Graphical User Interface| Command Line Interface/Tool|
|Response Time increase | Servers are mostly on Linux OS, Only GUI No GUI support bcuz of RAM,Memory,Speed|

- Undersatnding folders & files
  - pwd -> print working directory (currently in) , C:/ -> root directory , . -> current directory , .. -> parent directory
  - ls -> list all items
  - ls -l -> give this list format
  - ls -a -> show hidden files & folders
  - clear -> clear shell
  - ls -al -> combined of l and a

- **cd - change directory**
  - cd ./Downloads  -> move from current directory to Downloads
  - cd .. -> get back to one step backward
  - cd -> directly take you to home
  - cd ~ -> directly to home directory
  - cd ./Downloads/DSA  -> move from current directory to Downloads inside that DSA
 
- **Create Files & Folders**
  - mkdir CLI -> make directory with the name CLI
  - mkdir F1 F2 F3 -> Single time create 3 folders named F1 F2 F3
  - mkdir -p F4/F4_1 -> create F4 folder at the same time another folder under F1 named F4_1
  - mkdir F2/F6  -> Already F2 is there inside that F6 will be created
  - touch file.txt -> create an empty file with whatever extension you wnat
  - open script.js -> want to edit or work with file But open will not work on windows
 
- **Delete Files & Folders**
  - rm file.txt -> delete the file
  - rm f1/file.txt -> delete the file from f1 folder
  - rmdir CLI -> remove delete empty folder permanently of folder named CLI 
  - rm -R CLI -> delete even non-empy folder R means Recurcive
 
- **Copy and Move**
   - cp script.js f1/script.js
   - cp f2/index.html f1/index.html
   - cp -R f4 new
   - mv index.html f1/index.html
   - mv script.js hello.js -> for renaming use move only 
  
  > ***You can up & down arrow key for prev & next cmd which you executed***


# Section 5 : Git Introduction

## Intro
   
 






