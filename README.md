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
How do you create a project, How would you manage changes?
- index.html -> Version 1
- index.html + about.html -> Version 2
- index.html + about.html + contact.html -> Version 3
  
You will do all this Through Version Control System (VCS) and **Git** is most popular and widely used VCS.

## Version Control System
**Advantages of VCS**
- Version Control is a <ins>**manager software**</ins> responsible for **managing changes** to the computer programs, docs, websites & other collection of info.  
- Easy recovery of files/folders
- Rollback to the previous versions
- Informs about who, what, when, why changes have been made?

## History of VCS - Evolution
How VCS evolve over time?
- From Basic VCS to Distributed VCS
- Basically There are 3 types of VCS :-
  
1. **Local VCS**
   - It is very basic.
     ![Local VCS](https://devops2manager.wordpress.com/wp-content/uploads/2019/12/local_vcs.jpg?w=661)
   - Changes are stored in a database, along with timestamp.
   - Code in local system
   - Cons/Disadvantage -> Project can be lost, if your hard-disk is corrupted

  So although Local VCS solving problem of How would you manage & track timestamp of different-2 versions in database.
  But due to disadvantage of project getting lost We dont't use local vcs.
     
3. **Centralize VCS**
   Before going in details of Central VCS, Let's see some terminology 
   - **Repository** -> A directory(folder) where your files reside
   - Repository can be a local folder in your PC or a remote folder on a server
   - There are 2 types of repository :-
     1. Local Repository
     2. Central Repository
    
   - Centralized VCS contain just one repository i.e Central repository and each user can access it to work
     ![Centralized VCS](https://github.com/user-attachments/assets/ba79580c-0cbb-4f1f-aa23-1aa51e859a81)

     But there is no local Repository Copy is available to to the users locally.
     Everytime they have to update & commit on the server repository.
     That's the biggest disadvantage of Centralised VCS.
     
   - Cons -> What If Server goes down then nobody can work + if server hard-disk corrupt

     So, To overcome these, We will used **Distributed VCS** and Git is one of the distributed VCS
     
5. **Distributed VCS**
   This is one of the most popular VCS among everyone Software Engg, Data Scientists.
   ![Distributed](https://www.edureka.co/blog/wp-content/uploads/2016/11/Distributed-Version-Control-System-Workflow-What-Is-Git-Edureka.png)
   - Contains multiple repositories, each users has their own local repository & there is a central repository where the final code resides
   - push & pull to/from central repository by each users
   - provide **full back-up of the project**, all users will have full project
   - eg: **Git** is an example of distributed vcs
   - n local repositories --push-->.....<--pull-- 1 server repository
   - Everyone uses this Distributed VCS
  
   **Summary**
   ![3 Types of VCS](https://www.hallme.com/uploads/version-control-models.jpg)
  
## How is Git created?
- In 2005, by Linus Torvalds (creator of Linux Kernel on which many OS created like ubuntu,kali linex etc) ![Linux](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT9yLnU8DeLra28nxon_PTtSAYW1ipoSqYzDcthbm_sOcGaMdCyg5-E32tU&s)
![Linus Torvald](https://ideas.ted.com/wp-content/uploads/sites/3/2016/04/featured_torvalds_linux_ted_31.jpg)
- He started working on creating Linux Kernel from the year 1991, till 2002 everything going well.
- Linux Developer Community grows as big team, So they started using the Distrubted VCS which was **Bitkeeper** at that time.
- In 2004, Conflict started between Linus Torvald and Bitkeeper Founding team for free premium subscription.
- Linus thought Why should I pay for VCS a basic software Let's create own VCS.
- So They started creating Git in 2004.
  
## What is Git?
![Git](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqQ5Hg9lxzwQVOFMaIy693szddkxrILj462hC0FxjWClk_hZYdRhobvB0s&s)
- Git is **free and open source** distributed VCS designed to handle everything from mini to macro projects ***with speed & efficiency***
- Git Stores snapshot of your project (not differences)
  How?
  Git actually doesn't store the changes you have made rather take the snapshop of whole project at current
  | Differences in Versions |
  |-------|
  ![Git Difference](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS5mIKviC6XV6yjWyrQvBgyPnlGp0cpJwNHjw&s)

   | Snapshot of Versions |
   |----------|
  ![Git Snapshot](https://git-scm.com/book/be/v2/images/snapshots.png)

## Why Git & its Features
![Git](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqQ5Hg9lxzwQVOFMaIy693szddkxrILj462hC0FxjWClk_hZYdRhobvB0s&s)
- Why do we use Git?
   - **1. Collaboration** means when lots of developers work together for creating a project even if they're at remote locations.
   - **2. Storing Versions**
   - **3. Analyse the Code Changes**
- Features -
   - **1.Distributed** means different users will have the copy of original repository locally to work upon
   - **2.Everything is Locally** All the changes you will made locally once you satified & get green signal then only you will push and commit the changes on original repo of server unlike Centralize VCS where you will push or commit each changes everytime in original repo of Server. 
   - **3.Non-linear Development/Branching**
       - Most important feature of it, Suppose you're working on Google Website & you want to create one more feature but you're not very sure that this feature will work or not this might destoy other features that are already working fine.
       - ![Branching](https://book.the-turing-way.org/build/one-branch-210af77c43a042bcaf2b2c8d4ed00864.png)
   - **4.Secure/Integrity(Hashing)**
       - Since Git uses SHA-1, basically means Git uses Hashing & Crypto Algo for each commit each changes so that the changes we made will be very secure
   - **5.Speed(C)**
       - bcuz Git is written in language C and C language is close to Hardware.


# Section 3 : Setting Up Environment

## Installing Git
- [**git-scm.com**](https://git-scm.com/)
- Once you Download and install Git, You will see 3 options in your window searchbar  Git Bash, Git CMD and Git GUI
- We're going to use Git Bash, which is like similar to Command Prompt but more powerful than Command Prompt bcuz Command Prompt is only for Windows and we are going to use some Linux cmd on Git Bash.
- cmd line version -> check from your command prompt git --version
  
- Git Bash is terminal in linux, here act as simulator to run linux cmd on Windows OS. That's why we are preferring Git Bash

## Configure Git
Once you download & install Git Setup on your device, Now It's time to configure the Git.
- Why does we need to confiure it, It's something like logging in.
- Whenever you save some version of your project in the Git, So Git should understand who is making and saving the changes. bcuz lot of people/collaborator can make changes right, So You need to give your identity WHO ARE YOU?
- Who are you? bcuz you're going to be a user of Distributed repository So create your identity
- To give you identity to Git, basically you need to run below 2 commands:-
- You can check whether Git install properly on not by git --version
  ```shell
  git --version
  ```
  ```shell
  git config --global user.name "User_name"
  ```
  ```bash
  git config --global user.email "User_email"
  ```
**Summary**
![image](https://github.com/user-attachments/assets/eb7c5ad2-7f3d-4e82-a111-4ea211d95eee)


# Section 4 : Command Line Tool

If you don't know about Terminal, Command Prompt, PowerShell. 

Don't Worry.

There are two ways to interacts with your computer/device to work on files and folders and whatever you want to do.

|  1st Way    |   2nd Way  |
|-------|-------|
| GUI   |    CLT|
|Graphical User Interface| Command Line Interface/Tool|
| By clicking through Mouse on the folders, buttons etc to open....  |It's something like write command for every action you want to perform unlike clicking through Mouse |
| Why GUI? Not CLI | Why CLI> Not GUI |
|Response Time increase | Servers are mostly on Linux OS, Only CLI No GUI support bcuz of RAM,Memory,Speed constraints|

- **Terminal** for MacOS and Linux or **Command Prompt/PowerShell** for Windows or else we can use **Git Bash**  all of these are command line tool. 

- **Understanding folders & files**
  
  - **pwd -> print working directory** (currently in) , C:/ -> root directory , . -> current directory , .. -> parent directory
    ```shell
    pwd
    ```
    
    / slash means root directory and that's top most directory for Linux,MacOS,Windows
    
    After / Slash you will see Users folders or C/Users/PawanSingh
    
  - **ls -> list all items**
    ```shell
    ls
    ```
    
  - **ls -l -> give this list format**
    ```shell
    ls -l
    ```
  - **ls -a -> show hidden files & folders**
    ```shell
    ls -a
    ```
    
  -  **. (dot) means refering to current directory**
     ```shell
     cd .
     ```
     
  -  **..(dot dot) means refering to parent directory**
    ```shell
     cd ..
     ```
     
  - **clear -> clear shell**
   ```shell
    clear 
    ```
  - **ls -al -> combined of l and a**
    ```shell
    ls -al
    ```
    

- **cd - change directory**
  - cd ./Downloads  -> move from current directory to Downloads.Here, .(dot) stands for current folder and from there we will move to Download folder
  ```shell
    cd ./Downloads
  ```
  - cd .. -> get back to one step backward
    ```shell
    cd ..
    ```
  - cd -> directly take you to home
  ```shell
    cd 
    ```
  - cd ~ -> directly to home directory
  ```shell
    cd ~
    ```
  - cd ./Downloads/DSA  -> move from current directory to Downloads inside that DSA
  ```shell
    cd ./Downloads/DSA
    ```
 
- **Create Files & Folders**

  Let's see How do we create Files and Folders through commands
  
  - mkdir CLI -> make directory with the name CLI
  ```shell
  mfdir myphotos
  ```
  
  - mkdir F1 F2 F3 -> Single time create 3 folders named F1 F2 F3
  ```shell
  mfdir myfolder1 myfolder2 myfolder3
  ```
  ```shell
  mfdir myfolder1,myfolder2,myfolder3
  ```
  
  - mkdir -p F4/F4_1 -> create F4 folder at the same time another folder under F1 named F4_1
    So for that there is a flag -p
  ```shell
  mfdir -p myfolder1/photo/image
  ```
    
  - mkdir F2/F6  -> Already F2 is there inside that F6 will be created
  ```shell
  mkdir -p myfolder1/photo/image
  ```
  - touch file.txt -> create an empty file with whatever extension you want
  ```shell
  touch file.txt
  ```
  - open script.js -> want to edit or work with file But open will not work on windows
   ```shell
  touch script.js
  ```
   
- **Delete Files & Folders**

Let's see How in terminal we can delete files and folders
  - **rm file_name -> delete the file**
    ```shell
    rm script.js
    ```
  - rm f1/file.txt -> delete the file from f1 folder
    ```shell
    rm folder/script.js
    ```
  > **rm can only remove files not directory so to remove directory there is rmdir**

    ```shell
    rmdir folder
    ```
  
  - rmdir CLI -> remove delete empty folder permanently of folder named CLI
    ```shell
      rmdir folder/script.js
    ```
  > **In Case of Non Empty Directory rmdir doesn't work, So we have rm -R** 

   rm -R CLI -> delete even non-empy folder R means Recurcive
    ```shell
    rm -R  folder/script.js
    ```
 
- **Copy and Move**
  How do you copy(copy+paste) and move (cut+paste) files  & folders 
   - cp script.js f1/script.js copy file from my current folder to another subfolder of my current folder
  ```shell
     cp script.js f1/script.js
  ```
   - cp f2/index.html f1/index.html //copy your current folder file to any target folder
  ```shell
   cp script.js D:/js/
  ```
   - cp -R f4 new // copy folder with files to my current folder
  ```shell
   cp -R f2 new
  ```
   - mv index.html f1/index.html // move file from one folder to another
   ```shell
    mv f1/script.js f2/
   ```
   - mv script.js hello.js -> for renaming we don't have any rename cmd, use move(mv) only by cut paste with new new
   ```shell
    mv script.js newscript.js
   ``` 
  
  > ***You can up & down arrow key for prev & next cmd which you executed***





# Section 5 : Git Introduction
----------------------------------
![image](https://github.com/user-attachments/assets/c229a12f-86d3-496f-a2de-74104239d40d)

[Click Here for **Official Git Tutorial**](https://git-scm.com/docs/gittutorial)
## Intro

- Here we will start to learn about How we actually Work with Git?
- 
| **Category of Git Commands**|**Broadly 4 commands**|
|-------------------|--------------|
|**1. Creating Repository**| **git init**|
|**2. Making Changes**| **git add, git status, git commit**|
|**3. Parallel Development : Branching**| **git branch, git merge**|
|**4. Syncing Repository**| **push, pull, fetch**|

> **How to sync your local repository(Remote) with server repository(origin), So How to push/pull,fetch**

## Three Stage Architecture
- Let's understand What is Three Stage Architecture?
There are 3 different states(stages) of a Git Project
1. Modified
2. Stage
3. Committed

![image](https://github.com/user-attachments/assets/221f9dab-3524-45fc-b98d-2a135c29e8f9)


Whenever you're working with Git, You have your **git folder** called **git Project** 
Git Project will always have a folder called **.git** and It's a hidden folder.

Example :- 
Let's say you're creating your own website portfolio.
First file I want to add is **index.html**
Second file **style.css**
- **Modified**
We created these file in our current working directory that is .git hidden folder Here we are in Modified Stage( Working Directory Stage)
Once you satisfied that it looks good then save this version so that at any moment of time if I have come back to this version 1, I can do that.
So We have to save this in database(git repository).
we need to stage our file

- **Staging Area** basically means you tell thaat which files or what changes you want to store in the next commit.
> **Staging is likw whatever the changes you want to save in the next commit that area is known as Staging**

then what you do is commit.

- **Commit** basically means this is the final call, you want to save that So create a version for it.
once you commit, Version will be created, there is a folder called .git and .git folder will take snapshot for whole project.

Let's say after 10 days you want to add one more page **About.html** 
So You created the new file about.html and did some modification in old file index.html

Again Here you're in the working directory bcuz you have modified

 
## Initialising Git Repository
Let's see How to create a git repository, Here we're not talking about GitHub Repository here we're refering to creating a git repository on your local computer
> You know Repository is a project or folder as simple.
There are 2 ways to create a git repository
1. Start or Initialize your own local git repository
2. You can clone a remote repository to your local computer

- If you're starting any project from the very beginning itself then you will have to choose 1st way, You'll initialize your own local git repository
- If you're working with some other project website has been already been deployed & it's been 3 months and now your friend wants to contribute to your website. He wants to improve the functionality of your website. Your website is already a git project/repository. There is a folder of your website. Now your friend will not have to create own repository rather He will clone your project and then start working on that repository/project/folder.
  
> Later on We will see How to clone?

- **git init** means You're saying "Hey Git, initialize an empty repository for me."
```shell
   git init
```
☝️This will create a hidden .git folder, That's where git stores everything

```shell
git status
```
☝️ To track files and folders status

Practicles
1. Create a folder Git_Github>Myportfolio
2. Open it in any Code Editor VSCode
3. Create Index.html file
4. Open Your Terminal/Git Bash
5. Go to your Git_Github>Myportfolio folder
6. Now check the git status
![image](https://github.com/user-attachments/assets/9093e75c-5c05-4791-80e3-79bf1c4c9b44)

7. To create Git Repository on your local computer use the command git init
![image](https://github.com/user-attachments/assets/a501e5f5-58dd-4970-b6d1-a1b45ab9c60f)
![image](https://github.com/user-attachments/assets/0f4aef6d-3ce2-426b-9e1d-9704725d8b98)

> Note : **Before Initialize Git please check git status so that Don't initialize git again and again otherwise It will reinitialize git again**
![image](https://github.com/user-attachments/assets/73afa01f-98b0-4164-96b0-a884653ddbbf)

8. Till Here you have created index.html and initializ git. So at this time index.html is in modified stage bcuz git doesn't know about this file index.html
9. So If you check what's status? 
![image](https://github.com/user-attachments/assets/bf74a945-3163-4ede-b397-9e009a5ad436)
10. Git says - "Untrack file" as git doesn't know about the file So git want to understand that, that's why asking to add them into staging area and then commit & make version.
11. Once you commit, It will come into .git folder and git will know that index.html





# Section 6 : Tracking your Project
------------------------------------

## Tracking Files

## Commit Changes
   
## Lifecycle of the Status of a file

## Example of Lifecycle of the Status

## Logging the previous Commits

## Deleting a Git Repo


# Section 7 : Additional Git Commands
-------------------------------------

## Skipping the Staging Area

## What's the difference?

## I'm gonna Ignore you

## Remove and Move Files

## Untrack an already tracked file

## Unstaging and Modifying Files

## Git Alias



# Section 8 : Non-Linear Development : Branching
--------------------------------------

## What is Branching?

## Why do we need Branching?

## Creating a new Branch

## Switching to Branches

## Working with Branching

## Branch Logging

## Deleting a Branch


# Section 9 : Non-Linear Development : Merging
------------------------------------

## Merging Introduction

## Adding Funtionality

## Basic Merging

## Recursive Merging

## Merge Conflicts

## Resolving Conflicts

## Git Branching Workflow in Production



# Section 10 : Rebasing
------------------------------------

## Rebasing Introduction

## Rebase Branch

## How Git performs rebase internally?

## Keypoints of Rebasing

## When you should not use Rebasing?

## Merge Vs. Rebase

