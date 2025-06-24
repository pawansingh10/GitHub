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
We have see How do we stage file by using git add . but can we unstaged file, if yes how?

Whenever you make changes you do the Staging and then Commit to save that a version.
But suppose you have written code and that's not suitable & you already added the file for staging area, so what you can do is unstage file by using command **git restored --stage <filename>**

```shell
   git restore --staged <filename.txt>
```

![image](https://github.com/user-attachments/assets/e1791270-a6a6-4cb2-b50e-1afa39cb9213)

Let's say if by chance some of your youger brother/sister overwrite your code with random stuff in your contact.file & your page stop working functioanlly in that case you can revert back your previous version of that file by using the command **git checkout --filename.txt**, this command takes your file to the last version/commit
![image](https://github.com/user-attachments/assets/e8337a39-616d-4925-911a-042c3207633c)

```shell
   git checkout --filename
```
![image](https://github.com/user-attachments/assets/d8306259-48f2-498e-a3cd-cde2538593b9)


> **NOTE : 💀 git checkout --filename ⚡can be a dangerous command as it discards all your current changes in the current working directory So Be Very Careful while using**

Again if by any chance all the files has been changed then If you want to rollback to the previous commit. losing all newly modified files
```shell
 git checkout -f
```


## Git Alias
Let's see another feature of Git, which is how do we alias?
- **Alias** basically means another name of something
- Alias can be writtenn as a short name for a big term.
Suppose You have a very long command and you're using it frequently so you want alias that cmd with small keyword. So for that you have to configure alias
Example-
```shell
 git status
# We want to use it as st
 git st
```
Let's see How to setup Alias?

### Setting Alias
```shell
   git config --global alias.st status
```
☝️ git config --global alias.<new_short_name_for_cmd> original_command_name
Usage :- 
```shell
   git st
```
![image](https://github.com/user-attachments/assets/537c2759-1581-4e7b-92c4-862b97164096)

![image](https://github.com/user-attachments/assets/1f349f4b-9930-4117-ad2c-fd4aa3d6b2cb)

![image](https://github.com/user-attachments/assets/faf85485-9afc-415f-b287-0dc6289af79f)

> **We can set alias for complex commands**

# Section 8 : Non-Linear Development : Branching
--------------------------------------
Branching (Non-Linear Development) is the most important concept in Git. After Branching We will see how to Merge the Branches

Git actually follows the non-linear development or like Tree like Structure
1. Why Branches?
2. What are the uses of Branching?
3. How to create Branches?
4. How to work with Branches?
   
## What is Branching?
![image](https://github.com/user-attachments/assets/a5b1369e-0162-4cd9-a865-1a1f973e8d39)

 All the version system that we have like Apache Subversion, Mercurial etc etc all of them supports Branching bcuz Branching is one of the most important feature in Version Control system.
![image](https://github.com/user-attachments/assets/814e4d76-0df1-4c0f-aaa3-4732a2d46093)
[Click Here for more details](https://fullscale.io/blog/top-10-version-control-systems/#h-best-version-control-systems)

- A **Branch** in Git is simply a lightweight movable pointer [HEAD] to one of the commit
- Branching in other VCS like Mercurial, Subvertion etc are very expensive bcuz if any point of time if you're creating a branch They copy entire project But Git is really amazing VCS which is having killer feature bcuz branching in Git is very lightweight. You don;t have to wait for a lot of time while creating Branches and you can move back and forth from one branch to another branch directly.

 - **Branching :** Diverging from the main branch
 Basically means You can continue to work for a feature without affecting the code in the main branch.
You can take a branch from one commit and from there you can create your own branch and from there you started working on your feature. Now if any moment you feel your code is not working good you can simply delete your branch. So whatevr the changes you made for your branch files that will not affect the main line project(Master Branch)

- The default branch name in Git is **MASTER**
  We know that every tree must have at least one branch, Whenever you create a git project you always get one branch that is the main branch also known as Master Branch.

  So Master branch is the main line of your project So don't mess with this line

  If you want to mess with your code, try out new features, you're unsure that feature will work or not for that create new branch and if that feature is not working delete it. 

## Why do we need Branching?
Here, We will see Why Branching is important in any version control system.

Example - On your website you made 3 commits, in Version 1 you created index.html, in Version 2 you added About.html + modified index.html and in Version 3 you added contact.html section + modified index.html and few more commits. So this is your project main line which is your main/master branch, at this moment you only have one branch i.e main branch.

Now two of your friends saw you website and say you website looks fine but we want to contribute to your website, A is saying I can add animation your Website and B is saying I can add dynamic contents on your website. But You're also continuing working on your website, So you want them to work for your website but you don't want to they directly chnage your website as they might destroy/break your website by any chance.

So you can say okay you guys can work but my website is fully funtional and working at this stage you can create your own branches then A Will create a branch Animation and B will create another called Dynamic content

Let say A started working and made 4 commits and B also made 3 commits meanwhile you're also working on website and you also made 2 commits

After 10 days you see the progress of both A and B, You look at the A, the feature that he promised is working fine, but the feature that B promised is not as expected as your code is not working with adding the dynamic feature. So what you can do is ask B to delete the branch completely. So your code is exactly same as you want, you didn't made any change in your main branch but the code for A is working good and you want to use A Commits in main branch. So what you can do is Merge this branch into main branch & this process is known as merging.

> Even if you're working with a big team having 10+ collaborators working on same project all of them are working on different different features. Someone is working on Authentication/API/Frontend etc So they will create different different branches, you can create N number of branch and also creating branched deleting branches, moving between branches is super easy and lightweight in Git. So this is where we use Branching.

> Generally most of the time like 95% of time We will never commit on the master branch. We create a branch and if that branch works perfectly fine, then we merge that branch into main branch and that is also a commit called as **Merge Commit** 

- So this is reason why we require branching bcuz we don't want to exploit the main website/project/master branch.

## Creating a new Branch
Let's see How do we create branches in Git?

![image](https://github.com/user-attachments/assets/2cc38f13-66d0-4c4e-980c-94a13b7fb65e)

HEAD is a pointer that is in master branch and HEAD will always be at the last commit.
So If you add one more commit HEAD will fo go the last commit.

Before creating a Branch Let's See How many branches do we have right now?

- **Get all the branches in your project**
```shell
   git branch
   #Shows the available branches

   git branch -V
   # To know what was the recent commit in that branch
```
![image](https://github.com/user-attachments/assets/d6dd9cbc-6762-44f4-9257-adaa41a0ccf9)

- **Creating a new branch by using the command git branch <branchname>**
```shell
   git branch branchname
```
![image](https://github.com/user-attachments/assets/3d754573-b320-40e7-8ac2-cfd053b3fedd)

![image](https://github.com/user-attachments/assets/a19b1b62-aca6-46d6-8133-0b3acd3024d4)

☝️ Here, Head is point to master branch and both master branch and develop branch pointing to same commit bcuz there is no commit in develop branch after creating it same for the master branch in the master branch the last recent commit was that only.
But If you go into develop branch and create commits there then develop branch will grown on its own without affecting the master branch.

## Switching to Branches
Here we will see, How do we **move between branches**?

- **Checkout an existing branch**
```shell
   git checkout branchname
```
![image](https://github.com/user-attachments/assets/9609b8cd-af12-4c0e-95be-83dd144c9c83)
Once you move to your develop branch, HEAD will point to your Develop branch which was earlier point to main branch

☝️ The above command only work when branch will exist already. But if you want to create a branch and move immediately or checkout to that branch you can do that directly

- **Creating and Checkout to a new branch**
```shell
   git checkout -b branchname
```
Here -b stands for Create and new branch and directly go to that branch

![image](https://github.com/user-attachments/assets/197d97b5-e99b-4519-9244-08bb4410cce8)

Similarly at any time you can switch to one branch to another by using git checkout <branchname>
![image](https://github.com/user-attachments/assets/214d7400-89a5-4ad6-b2cf-6ee0211ae407)


## Working with Branching
Here, We are going to work with branches
![image](https://github.com/user-attachments/assets/ea8b5218-96e9-492d-a832-d45dc20d8054)

![image](https://github.com/user-attachments/assets/96053c20-cb69-4eb2-b0d9-754e30a50210)
![image](https://github.com/user-attachments/assets/68ccfe7b-283a-4987-b92d-59af9419fa67)

![image](https://github.com/user-attachments/assets/d2e2978d-593f-45c2-98d7-203b52ff2549)
☝️ Here you are in develop branch and made a commit so head is pointing to this recent last commit.
So If you want to go the master branch you can switch by using git checkout master there you will see head will again point to last commit which was happend in master branch and we are no longer accessing the develop branch.
![image](https://github.com/user-attachments/assets/4fbe4cdc-59ea-47f6-87ae-e2032464861e)

![image](https://github.com/user-attachments/assets/1e60253d-c24f-4365-8e78-42377714fcea)

![image](https://github.com/user-attachments/assets/1c47593a-9740-4d10-95f3-0cb1428c4e73)


## Branch Logging

Git will warn you if when you made some changes in your develop branch and trying to move to master branch without committing the changes in develop branch.
![image](https://github.com/user-attachments/assets/f2eff5d4-c657-4a80-a453-e40b63ac3199)

![image](https://github.com/user-attachments/assets/47b9d464-1e19-497c-866a-8ce861a55a16)

![image](https://github.com/user-attachments/assets/8fab296d-7bdd-4f42-a7a5-168af207c7b9)
☝️ Here you will see master branch and ux branch but not develop branch, So where is it? Develop branch is now diverged as it has different commits from the main branch that's why you are not seeing it.

We can see all the branches at once in console by using the commands
```shell
   git log --oneline
   git log --oneline --graph --all
```
![image](https://github.com/user-attachments/assets/709388d0-62d4-4d45-a34d-15a38e40baa4)


## Deleting a Branch
Let's see, How do we delete branches?
Why/When do we actually need to delete the branches?
The idea behind delete any branch is when you merge all the changes in master branch then we can delete our develop branch
- 

- **Deleting a merge branch by command git branch -d branchname** here d stands for delete
```shell
   git branch -d branchname
```
![image](https://github.com/user-attachments/assets/131f8f30-a625-4081-9827-c6cb7bfc7d34)
So If you branch is already merged into main branch then only you can delete you branch.

![image](https://github.com/user-attachments/assets/ff921500-6e4c-474f-b73b-f0e13b7495a2)


- **Deleting a non-merge branch by command git branch -D branchname** here D stands for delete forcefully
```shell
   git branch -D branchname
```

![image](https://github.com/user-attachments/assets/8b38ba7e-aead-49e1-bbe0-0d0fda9913b1)



# Section 9 : Non-Linear Development : Merging
------------------------------------
Here, We will see Merging, Merging of Branches.

Let's understand, Why is it important to merge branches?

![image](https://github.com/user-attachments/assets/defe07be-90b8-4cd9-8714-1d5afd76b127)
For adding any feature we create new branch, but why? bcuz as a precaution we don't want to commit directly in master branch so that I don't even accidently mess up with master branch. This is divergence that I'm taking another path and making changes there committing those changes once I satisfied that this branch is working successfully and page is looking good then you can merge these changes with master branch with a new commit. That's where Merging helps.

## Merging Introduction
Merging will actually take all the changes from your new branch and it will merge into the main branch. bcuz master is our code in production.

## Adding Funtionality
A requirement came from manager to add a new feature in your live ongoing project.
So What you will do is Create a branch named New_Feature and start making changes and committing those changes into your New_feature branch.

## Basic Merging
Suppose while you're working on you New_Feature branch your manager came & said Hey I need these modification in our Home page by EOD today.
So How will you do that first thing you will do is first commit the changes whatever you have made in your New_Feature branch other if you will forcefully jump into ane branch to another without committing then in that case your code will be dicarded. So commit it and then swtich to the master branch create another new branch for the Home_Page modification make changes commit it and then be very sure your code is working fine once you're sure then merge the changes into main branch with a new commit and return switch back to your New_feature branch where you had working and commited your code.

- To merge two branches in this case, If you want to merge changes of impFix branch into master branch, first thing you have to do is checkout master first.
```shell
   git checkout master
```
```shell
   git merge impfix 
```
![image](https://github.com/user-attachments/assets/47526561-1575-447a-8375-4d2be02e951e)
![image](https://github.com/user-attachments/assets/fd8b4bef-cf7d-4067-82f8-ae24bef1c1e6)
☝️ Here in the above case you didn't made any changes and any commit in your master branch, So It was easy to merge bcuz the only changes and commits are done in your impfix branch not in master branch.

![image](https://github.com/user-attachments/assets/e15ebb71-b556-4e24-a1bc-b4f6871eb321)

once you merge the branch into main branch you can delete your branch
![image](https://github.com/user-attachments/assets/726297cc-f079-4679-ae92-409678aa94ad)

But in case of changes & commits in feature branches as well as changes are commits in master branch as well, there you will see a different type of Merge known as Recursive Merge.

## Recursive Merging
- Once your priority task which was given by your manager is done, Let's go back to the development branch bcuz we were developing the contact form
```shell
   git checkout develop
```
The changes that we made in impfix is not reflected in in this develop branch, why is it? bcuz we have merged impfix with main branch. we haven't merge with develop branch.
So one way is you can merge those changes into your develop branch by using **git merge master** through this all those changes files folder all will be reflected in your develop branch.
But this is not required bcuz we don't want to keep the develop branch updated, we always only neeed to keep master branch updated.

There's no point to updating develop branch. So let's continue developing our feature contact.html

So Now master is pointing to recent commit which was done while we merged the impfix with master and in our develop branch we made two commits. So Now we have to merge our both commits of develop with the recent commit of master. So this will be not easy as we did in case of only commit happend in impfix branch only not in master branch.
Let's see How we can do that.
![image](https://github.com/user-attachments/assets/7176a5f6-f991-4211-8007-cb2cdb1a72ec)

Now we want to merge the changes of the master branch and merge the changes of the develop branch
1. First come to the master branch ```git checkout masterbranch```
2. Second Step will be merge ```git merge develop``` Here the only difference you will see is as soon as you hit enter, It will ask you to give a message although it is not required the messahe is already there "Merge branch develop" This will be the commit message. Now you can ask where does this commit come from? So may be you can remove the commit message or overwrite you can easily do. But We are okay & happy with the Commit message to let's press **esc + : + w + q**  here wq stand for Write and Quit to skip commit message.
3. So what you will see is **Merge made by 'recursive' strategy** unlike in the previous case there **Merge made by fast Forwarding**
![image](https://github.com/user-attachments/assets/17d979a3-c658-4163-84ec-1cc70d275062)

4. Now you will see your contact.html page will be updated as changes has been merged and commited to master branch.
5. Now Your Master Branch is up to date which contains the changes from impfix branch as well as develop branch
![image](https://github.com/user-attachments/assets/e65fccd6-13df-4668-a2fe-097b74f7741a)

It was not that simple as it was in the case of fast forward. 
- How does Git merges two branches if they do not have the same commit?
1. We have to merge develop into the master branch and their common ancestor(commit) in both branches is one where the diverging started.
2. So Both Master branch and develop branch meet at the common ancestor there, at that point the code in both branches were exactly same.
3. But After this Master branch made some other changes and commits and develop branch also made different changes and commits.
4. Now what git will do is - It will start checking what are the chnages made by master branch? and What are the changes made by develop branch?
5. And Git will try to merge both of them recursively. So this is something called **3 Ways Merging**
6. At the end there will be new commit "Merge develop recursively"
![image](https://github.com/user-attachments/assets/6dac4cc9-cc7d-4f4d-98b3-40e6efbbc966)

7. New Commit name is Merge develop and It will have 2 parents bcuz the content is not coming from one branch, rather content is coming from 2 branches one is from master branch and another one is develop branch
8. So This new commit or snapshot has 2 parents and Master will point to this  latest commit.
![image](https://github.com/user-attachments/assets/17c411c2-bba0-4a7d-8c44-98786ae8087a)

## Merge Conflicts
Here we will see, Merge Conflicts.
It's an interesting idea bcuz It annoys as well as it lead to conflicts and Conflicts are never encourage.

> **Change in a file made by 2 different branches, trying to get merge results in a Merge Conflict**

So, Merge conflicts happens when two different branches try to manipulate or change the same line of code in the same file.
Example - We have a file home.html, and there is heading is "Pawan Singh"
          Let say two branches B1 anf B2, Branch B1 want to change heading to "Pawan" and branch B2 want to this heading to "Hi, This is Pawan!!"
          Now when you try to merge these changes what  will happen? They both will result in a conflict bcuz Git will be not able to understand which change should I accept? that's lead to Merge Conflict.

- **Let's see How a Conflict look like?** through code.
  1. We have to change Heading in home.html
  2. So create a branch B1
  3. Also create another branch B2
  4. Let both try to modified the heading according to their own wish
  5. Now we want to merge B1 and B2, Let's see what will happen?
  7. Here you will see conflict arises bcuz B1 have changed the Heading and B2 also changed the heading, Now Git will not understand which changes It should accept?
  ![image](https://github.com/user-attachments/assets/2d31039c-ce59-4100-ab25-22080838a96c)
  ![image](https://github.com/user-attachments/assets/9c365d11-5b93-46bd-ad5d-87beaed0fd51)
  ☝️ Automatic Merge failed, this means that Git can't automatically take all the changes from from the branches and merged automatocally. So you need to manually fix them
      Fixed these conflicts and then commit the results.
  We will see how to fix them?
  
  
> **😊 In real world, Merge conflicts happens alot!!** when two programmers/collaborators works on the same file.


## Resolving Conflicts
Let's see How to resolve the Conflicts?
By the if you have VS Code, It as a property which will show you the conflict is highlighted in the Editor.
![image](https://github.com/user-attachments/assets/7186ee73-9591-4f5c-9289-04fd92a479dd)

By the way if you look for the git status in b2, you will see unmerged path
![image](https://github.com/user-attachments/assets/06bf5920-0af7-4e46-aee5-b65880f27ca2)

Now you have to make the changes manually in the code selection any of the them either current or upcoming save them and then add and commit, merge will be successful.
![image](https://github.com/user-attachments/assets/f147f93b-5148-49e2-a66d-fdc8b01f36ca)

> You can see which branched are merged or which are not? by sing the command
```shell
    git branch --merged
    git branch --no-merged
```

## Git Branching Workflow in Production
Here, we will see, How actually Branching look like in production?
Whenever we do the work of branching and merging in the actual production, there are always two type of branches.
1. **Long Running Branches** - Branches that works for very long time like master branch, development branch actually till the project survive.
2. **Topic Branches** - Branches which are related with basic small topics like Authentication, UI Changes, these topic branches live for a short period of time till the functionality is there once you are done with functionality merged changes into development or master branch then you will delete these Topic/Short Term branches
   
![image](https://github.com/user-attachments/assets/961ccf1a-afe9-47c4-97b3-6aef04099039)


# Section 10 : Rebasing
------------------------------------
Here, We will see and understand, What is the idea about Rebasing?
As we know about Merging, How to work with Branches and How to Merge Branches?
- 
**To integrate the changes from one branch into another** There are 2 ways:-
1. **Merge**
2. **Rebasing**

Example - Suppose you're in master branch and you want to add one more functionality on your project. So you create a different branch called ImproveUI. So once you're done or finish the work on that branch you have to take those changes and you have to integrate(Merge) those changes into master branch.
 So we can do this by two different ways.
 One way is **Merging** which we have seen already
 Other way is **Rebasing**
 
## Rebasing Introduction
The purpose of Rebasing is to take the changes and integrate into the different branches.
It's same like Merging, the eventual outcome will be same as Merging, But the process of integrating changes are different from Merging.
When we have to use Merge and when we have to use Rebase?

Let's see code.
1. First create a branch named experiment branch
2. Create one file called Experiment.html
3. Made Some changes in Experiment 1, git add . + git commit
4. Again made changes in Experiment 2, git add . + git commit
5. 

- With the **rebase** command, you can take all the changes that were committed on one branch and replay them on a different branch.

Let say we have lot of commit in our master branch, and from a point we created a new branch experiment and we did 2 commits in experiment branch, Also simulatenously we did one more commit in master branch as well.
If you do the merging, Merging will take all the changes from experiment branch and master branch and will create  commit.
But If you do rebasing, Rebasing will take those two commits from experiment branch and it will  create copy for that and delete those twro commits and It will append which basically means replay those same changes/commits to master branch and your master will commit at the latest commit location. and It look like Linear changes.

![image](https://github.com/user-attachments/assets/fd50b570-2c2d-4389-9125-85c92f4eed2d)

## Rebase Branch

So Let's do Rebasing, If you want to rebase experiment branch into the master branch, you need to be at the experiment. This is exactly opposite case in Merging.
![image](https://github.com/user-attachments/assets/1fec0513-e205-42be-a55b-b90a277ba70b)



## How Git performs rebase internally?
Let's see How Git performs rebase internally?
This is a 5 Steps process:-

example - We have few prior commits in master branch, from the latest last commit we created a experiment branch. And experiment branch has two commits and master branch also has a commit meanwhile.
          Now Let see How rebasing happen at this moment.

1. Git Pointer goes to the common ancestor of the two branches(the one you're on and the one you're rebasing onto)
2. Git will Gets the diff introduced by each commit of the branch you're on.
3. Git will Saving those diffs to temporary files
4. Git will Resetting the current branch to the same commit as the branch you are rebasing onto.
5. Finally applying each chanage in turn

Let's look at How did we update our master branch to the recent commit that experiment branch has done?
![image](https://github.com/user-attachments/assets/14910b07-c8eb-4936-beaa-71ac7df99027)

So Now if you delete experiment branch
![image](https://github.com/user-attachments/assets/e6aa0e6b-2353-45f9-813b-74476f394a2e)

So It look like we have linealy develop this feature but this was not the case We created a branch made changes and commits and Rebase into the master branch and then merge state.

## Keypoints of Rebasing
Basically advantages of Rebasing
1. No difference in the end product of the integration, but rebasing makes makes for a cleaner history.
2. The log history look like a linear histroy. I t appears that all the work happened in series, even when it originally happened in parallel.
3. often, you'll do this to make sure your commits apply cleanly on a remote branch.

> When we have to work with collaborators and the project that we're contributing to doesn't belong to us.Someone else maintain that project.

> So What we do is create a local branch and rebase that branvh into your master branch and then send that code into the central repository server so that others can also see the same code. and they have to just take master branch forward like they have to do just fast forwarding that's it.

> Most of the time when we do rebasing it's bcuz we are contributing with some open source software/project, different maintainers and we don;t have to trouble them by making a lot of other branches, pishing those branches into their repository. 

We create a local branch, we rebase into master branch and then send this whole complete code to their repository.

## When you should not use Rebasing 💀?
Rebase has one major disadvantage 
 
 **Do not perform rebase commits that exist outside your repository and that people may have based work on.**
Example - 
 When you rebase stuff, you're abondoning existing commits and creating new commits that are similar to existing commits but different.(Content & everything will be same but commit ids will be different)

 Let say you have existing prior commits in master branch at a point where you have the last latest commit there you are creating a experiment branch and in your experiment branch you made 4 commits and you master branch 2 commits. If you are working on other repository 

 - Most of the time when you're working on a local system or a local repository create a branch, rebase it with master branch and then push the whole code to the central repository so that the maintainer of the central repository/project thinks that you have developed/committed 5 commits and that is in a linear type of branch and maintainers will have to simply do the forwarding of the master branch.
 - But if you think that a lot of other collaborators are there and someone is relying on your commit then don't rebase on the central repository. 


## Merge Vs. Rebase

We have already seen what's difference between Merge Vs Rebase

One point of view
Commit history is a reord of **what actually happened**. then you can use Merging

The opposing point is
The commit history is the **story of how your project was made**. then you can use Rebasing



