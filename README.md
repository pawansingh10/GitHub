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
Here, We will see How does Git actually tracks you Project, How Git manages all the changes that you are making in your project?
All  the differt different Versions can be tracked with the help of Git.

## Tracking your Files
In your current working directory at any moment there can be two different types of file **1. Tracked files** and another is **2. Untracked files**

- Each file in your current working directory can be in one of the two states : **tracked** and **untracked**.

  | **Tracked files** are the files that Git knows about.|
  |------------------------------------------------------|
  | **Untracked files**, any files in yoiur working directory thatwas noty in your last snapshot and is not in your staging area is **Untracked file**|

Example : Suppose Index.html, in the version 1 there was only one file i.e. index.hml and Git knows that in version 1 there is only one file. Later you introduce a new file which is About.html
    now Git deosn't know about About.html. So, Git will say this is untracked file.

> Git is integrated by default with the one of the most popular Code Editor VS Code
![image](https://github.com/user-attachments/assets/9c71003b-2d62-41fb-af5b-d850df4cbc5d)

Now for the first time in our project we created Index.html and Git doesn't know about it. So We need to put it into Stage Area bcuz this is the second step from there we will commit and then Version will be created & Git knows everything inside .git folder so obviously will know about index.html

So How dow we add this to Staging Area?
Well, for that there is command for Tracking a specific New file or all the files & folders at once

**git add <filename>** basically means You're saying, Hey Git add this file to staging area

**git add .** Here why dot bcuz dot always refers to current directory and whatever the files and folders are there in current repository all will be staged together.
```shell
# for one specific file
git add index.html

# for all files and folders
git add .
```
![image](https://github.com/user-attachments/assets/d69cd96f-7a6d-4de3-b59a-27d015d5e577)
![image](https://github.com/user-attachments/assets/ca6f4ce3-94d7-42f4-8325-10f9f3995c98)

> **You can also unstage a file or files and folders** (use "git rm --cached <file>..." to unstage)

## Commit Changes
Here, we will see How do we commit changes? and that is the 3rd Step

Moving files from staged area to the git folder is called a **commit**

Making Commit, Creates **Version/Snapshot** of your project.

We can do commit by using the command **git commit -m "Your commit message"** which means you're saying Hey Git commit this file -m is flag here stands for your message why did you make these changes.
```shell
git commit -m "add index.html"
```
![image](https://github.com/user-attachments/assets/86d8d49e-7464-420b-a7a9-449a4478e372)

Now after commit, Git will create the version and git will remember this file life long means till this project exists.
If you delete the file Git will rememeber that as well Oh you have deleted this file.

![image](https://github.com/user-attachments/assets/8466370b-6920-4cf4-a4fe-8fa3853291e4)
Here you can see the index.html file is removed from the git section in VS Code as We have commited the file. First Step, We created index.html in git repository, Second step we move index.html to Staging Area and Third Step we committed the index.file. So Version 1 of it created and file status changes from Untracked to Tracked to Added.

   
## Lifecycle of the Status of a file
Here We will see Life Cycle of a File which is tracked or untracked from Untracked till commit

There are 2 types of file Tracked file and Untracked file, If the file is tracked what are the different status

In version 1 We have file called index.html which is actually a tracked file because we have committed index.html
So Git knows that Git need to track this index.html file

Now, You add a new file About.html So this file is in the working directory but this file is not tracked right now because this About.html was not in the Version 1. So About.html is untracked file.

Tracked file (Index.html) can be either unmodified, modiefied or staged. So right now our index.html is in unmodified stage bcuz We had already committed this & as of now we have not made any changes in index.html

But if I make some changes in Index.html like adding any new section or any new line or new word or even one character. It will go from Unmodified to Modified stage. After modified again you stage (git add index.html) It will goes in Staged Area, once you're in staged area if you do commit (git commit -m "New page added") Version 2 created, It will gain goes to unmodified stage.So basically this is the life cycle of Index.html till version 2.

But If you have a new file like About.html, Here About.html will have nothing to do with Modified or Unmodified stage because this is new file & this new file is untracked So when you add (git add About.html) that file then it will directly goes to Staged Area. Once It is staged area you can do commit (git commit -m "added About.html") new version will be created and It will be moved to the Unmodified Stage. So this is the life cycle of About.html till version 3. 

![image](https://github.com/user-attachments/assets/1effbecb-5476-4bc1-b948-1db959b348b1)


## Example of Lifecycle of the Status

Let's Create About.html file and see.....

![image](https://github.com/user-attachments/assets/5a175d42-a83f-495b-8800-75695d8d5434)


![image](https://github.com/user-attachments/assets/769c4027-3212-4b39-9521-7b83cc8ef6dc)

Now Let's Modify our index.html file

![image](https://github.com/user-attachments/assets/73733bc4-9e82-4296-b6b3-99848a6473c1)

![image](https://github.com/user-attachments/assets/4ea2c9dc-90ea-461d-af06-e5cd3c5d3274)

![image](https://github.com/user-attachments/assets/e7ea771f-40a9-490c-936e-cb862b1862b2)

![image](https://github.com/user-attachments/assets/a78b187a-8a10-4213-870d-1cc2ec07ccaf)

![image](https://github.com/user-attachments/assets/071a3cb8-5daa-42f4-8933-d23675587cb7)

![image](https://github.com/user-attachments/assets/71ee61ae-7f4e-4f5b-a696-71f28d8e7e1f)


## Logging the previous Commits
Till now, we have made lot of changes basically we can say we created first version when we added index.html, second version was when we added about.html and third version when we modified for adding subheading so on and so forth. So we want to see all of these version we can see by using cammand **git log**

- **git log** means You're saying Hey Git show me all the different commits for versions of my project

```shell
  git log
```
![image](https://github.com/user-attachments/assets/a1a604e8-0746-4147-9a97-c9121d4d6da4)


 ☝️ The most recent comment will come at the top.
 
 ☝️ You will see Commit ID which is kind of a very long string also called as Hash ID (SHA 1,provides integrity & safety It is bcuz of Hashing). You will see all the commit has its unique IDs having a very long Hash Number which uses the algorithm **MD5**, which is Cryptographic Algorithm to convert any string into endcoded version. 

☝️ You will see **HEAD-Master**, Master is basically a branch.

☝️ You will see **Author : <name>**, **Date : Day Mon Year Timestamp**. Here Git knows Author name? It is us who told Git while configuring told that whatever commits happen with this computer/PC the User_name will be mine what we passed while configuring **git config --global user.name "User_name"**

So this was about the most recent commit similarly you will see another commit for second most recent commit and so on.

- You can see you commits in one line instead of parameter by using glag oneline, like this **git log -oneline**
  
```shell
  git log --oneline
```

![image](https://github.com/user-attachments/assets/443392e3-2e5a-449e-9d63-6a989d64ceaa)

> We learn about how you can see all the history of a project if it is git project from the beginning till the end.
> These commits or Versions exits why? So that you can also roll back to any version if you want. 

## Deleting a Git Repo
Here We will see a **very very dangerous command** which is to delete a git project and that is **rm -rf .git**

```shell
   rm -rf .git
```
☝️ Here rm is for **Remove** and -r is for **Recursively** and f stands for **Forcefully** even if it's not allowed delete everything.

**💀 Disclaimer : You should never use this command until and unless it's really require for you to run**

![CautionWarningSignGIF](https://github.com/user-attachments/assets/eb90804a-a7fb-4641-9eb9-b9e564d35fd2)

If you delete the hidden folder .git by any chance by intentionally or unintentionally, you will lose all the git history,versions, changes you made and it will be untrackable.

![image](https://github.com/user-attachments/assets/818b7245-6214-4059-bccc-fc5c0d4b4b1a)
![image](https://github.com/user-attachments/assets/ea814b19-8bf9-4886-b023-21363a40aa53)
![image](https://github.com/user-attachments/assets/d5eb5688-b958-41b9-8805-922b5ed6e2ac)




# Section 7 : Additional Git Commands
-------------------------------------
Here we will some more git commands

## Skipping the Staging Area
How do you skip the staging?

Staging area is basically the area where all your files are getting ready to commit.

```shell
git commit -a -m "Commit Message"
```

For the first time before you have any version, you can't skip staging (git add .)

Most of the time in a project ot git project you do not create every time, Most of the time you change or modify existing files.

![image](https://github.com/user-attachments/assets/a93b8518-4000-470a-b45b-6a4671c524d8)

![image](https://github.com/user-attachments/assets/6c5e9848-819b-49af-9499-508e8be79365)


## What's the difference?
Here We will see another interesting command **get diff**

- If you want to know exactly what you changed, not just which files changed -- you can use **git diff** command

```shell
   git diff
```
☝️ Here diff stands for difference, it tells you the difference. Difference? difference between file what files? files that are currently there in your present working directory and the files thar are being staged already.

There are 3 stages, 1.Working Directory 2.Stageing area 3.Commit

Git Status tell only about this file get modified but doesn't tell what exactly the change is being made in these files. To overcome this we use command **git diff**

![image](https://github.com/user-attachments/assets/2c2f754d-f8cf-4538-8fff-217f4cdbffd2)

But if you add the file to staged area, you won't be able to see the difference this bcuz the changes you have made is already staged 

![image](https://github.com/user-attachments/assets/1bf3ffa7-3feb-4fc5-bcbe-bb7ed7c4504b)

So If you want to see diff of the file that is being already staged then you can do by using the flag **git diff --staged**
```shell
   git diff --staged
```
![image](https://github.com/user-attachments/assets/cb21805f-fc93-4475-88b7-d976e151d780)


## I'm gonna Ignore you
Here, We will How we will ignore some files? but why?

Often times, we do not want Git to keep track of some specific autogenerated files like logs or build files etc.

To avoid them, you can list files or a pattern for files in **.gitignore** file. .gitignore is also a hidden file so what we can do is create this .gitignore file and whenever you see that there is a file called .gitignore, you can write all the files that you to ignore in this file.

So If you don't want the git to recognize the file/files these files as known file or tracked file by the git. So you can list them in .gitignore. There are two ways to do so :-
1. You can just directly write the name of those files and folders which you want to ignore by git
2. Or Alse You can also use the Pattern, means regex:reglar expressions

Because we write errors.log in .gitignore file, now git ignore the errors.log file that's why it's not showing errors.log as untracked file
![image](https://github.com/user-attachments/assets/17897315-96bc-4bf1-b62a-f7fbcb65b17b)

![image](https://github.com/user-attachments/assets/450a35f6-4fdd-4801-acba-d137dc705a24)

![image](https://github.com/user-attachments/assets/ebf5e1be-48de-4e7d-b7c7-4362f4faf0df)

☝️ This is how you can ingore all the files and folders that you want to ingore by the git. It is not necessary to ignore but if you want in case.


## Remove and Move Files

Here, We will see How do we move and remove files from git.
We have already seen how to move and remove files from our folders while getting familiar with Command Line Tool.

Why Git is required to move and remove or delete files/folders?
When you delete or move files using git tool, then it also stages the changes, whatever the changes you will do it will automatically get stages. So You don't have to stage the changes.
Suppose you're deleting some files or folder, So you don't have to explicitly add in to the staging area.

- **Moving & Removing Files**
These commands stage the changes automatically. You don't have to stage explictly.
```shell
   git rm <filename.txt>
```
![image](https://github.com/user-attachments/assets/674cd1bb-556d-4153-ae53-68ad4b67fdc8)

```shell
   git mv <filename.txt> <newfilename.txt>
```

![image](https://github.com/user-attachments/assets/87aac324-0082-4575-95d7-fa5c542072d0)

![image](https://github.com/user-attachments/assets/a77594c5-1340-4af3-8162-497a5b9a2a19)



## Untrack an already tracked file
Sometime even if you keep the file name in .gitignore file It will not work that is bcuz if git already knows this file in previous version before you created the .gitignore file & add it to .gitignore.

Although you have written that in .gitignore file but since git had already started from the previous version to track the file So It will continue to track until and unless you explicitly give a command to untrack this file.

So You can do that by using cammand **git rm --cached <filename>**
```shell
   git rm --cached filename.log
```

> **Git doesn't  track the empty folders, until and unless you create some file inside**


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

