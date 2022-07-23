![Git](https://git-scm.com/images/logos/2color-lightbg@2x.png)

# Git!

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Originally developed as an open source project in 2005 by the creator of the Linux operating system, it is a matured and actively maintained environment

# ⭐️ `Star us`

If you like this information, please star it, each star makes me very happy!

# 🤝 `Need help?`

If you need help with setting up the boilerplate or have other questions - don't hesitate to contact me via Linkedin and I will check asap. [Linked link](https://www.linkedin.com/in/duc-cong-nguyen-b7b9b8212/). I will be very happy when answer your questions.

# 🚀 `Quick Start With Github`

### 💿 To create a new repository on the command line

```bash
echo "#Git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M "main"
git remote add origin https://github.com/{username}/{reponame}.git
git push -u origin "main"
```


or push an existing repository from the command line

```bash
git remote add origin https://github.com/{username}/{reponame}.git
git branch -M  "main"
git push -u origin "main"
```



---

# 🧭 Table of Contents
-   [⭐️ Star us](#️-star-us)
-   [🤝 Need help](#-need-help)
-   [🚀 Quick Start With Github](#-quick-start-with-github)
-   [🧭 Table of Contents](#-table-of-contents)
-   [❓ Why Git?](#-why-git)
-   [✖️ How to start with Git and Github?](#-how-to-start-with-git-and-github)
    -   [Git Workflow](#-git-workflow)
    -   [Start using Git](#-start-using-git)
-   [📦 Some git popular commands](#-some-git-popular-commands)
-   [📥 Download](#-download)
-   [🧙‍♂️ Community](#️-community)

# ❓ `Why Git?`
## 1. Performance
Git performs very strongly and reliably when compared to other version control systems. New code changes can be easily committed, version branches can be effortlessly compared and merged, and code can also be optimized to perform better. Algorithms used in developing Git take the full advantage of the deep knowledge stored within, with regards to the attributes used to create real source code file trees, how files are modified over time and what kind of file access patterns are used to recall code files as and when needed by developers. Git primarily focuses upon the file content itself rather than file names while determining the storage and file version history. Object formats of Git repository files use several combinations of delta encoding and compression techniques to store metadata objects and directory contents.

## 2. Security
Git is designed specially to maintain the integrity of source code. File contents as well as the relationship between file and directories, tags, commits, versions etc. are secured cryptographically using an algorithm called SHA1 which protects the code and change history against accidental as well as malicious damage. You can be sure to have an authentic content history for your source code with Git.

## 3. Flexibility
A key design objective of Git is the kind of flexibility it offers to support several kinds of nonlinear development workflows and its efficiency in handling both small scale and large scale projects as well as protocols. It is uniquely designed to support tagging and branching operations and store each and every activity carried out by the user as an integral part of “change” history. Not all VCSs support this feature.

## 4. Wide Acceptance
Git offers the type of performance, functionality, security, and flexibility that most developers and teams need to develop their projects. When compared to other VCS Git is the most widely accepted system owing to its universally accepted usability and performance standards.

## 5. Quality open source project
Git is a widely supported open source project with over ten years of operational history. People maintaining the project are very well matured and possess a long-term vision to meet the long-term needs of users by releasing staged upgrades at regular intervals of time to improve functionality as well as usability. Quality of open source software made available on Git is heavily scrutinized a countless number of times and businesses today depend heavily on Git code quality.

# 📦 `How to start with Git and Github?`

## 1. `Git Workflow`
![repo](https://media.discordapp.net/attachments/992269395214733362/999922554498195607/unknown.png)

The core components: 
-    Working Copy: consists of files that you are currently working on. You can think of a working tree as a file system where you can view and modify files.
-    Staging area: is where commits are prepared. The index compares the files in the working tree to the files in the repo. When you make a change in the working tree, the index marks the file as modified before it is committed.
-    Repositories (local and remote): is the “container” that tracks the changes to your project files. It holds all of the commits — a snapshot of all your files at a point in time — that have been made. You can access the commit history with the Git log.

## 2.  `Start using Git (with Github on windows)`
### 2.1. Create a new repo
Access [github](https://github.com) to create a new repo (Make sure that you already have a github account)
-   Step 1: In the upper-right corner of any page, use the  drop-down menu, and select New repository.
![step1](https://docs.github.com/assets/cb-11427/images/help/repository/repo-create.png)
-   Step 2: Type a short, memorable name for your repository. For example, "hello-world".
![step2](https://docs.github.com/assets/cb-25139/images/help/repository/create-repository-name.png)
-   Step 3: Optionally, add a description of your repository. For example, "My first repository on GitHub."
![step3](https://docs.github.com/assets/cb-26377/images/help/repository/create-repository-desc.png)
-   Step 4: Choose a repository visibility
![step4](https://docs.github.com/assets/cb-20877/images/help/repository/create-repository-public-private.png)
-   Step 5: Select Initialize this repository with a README (Optional)
![step5](https://docs.github.com/assets/cb-49938/images/help/repository/initialize-with-readme.png)
-   Step 6: Click Create repository.
![step6](https://docs.github.com/assets/cb-19887/images/help/repository/create-repository-button.png)
### 2.2. How to push a file to remote repo?
Open terminal in your project
```bash
-   Step 1: git init
-   Step 2: git add <your file> or git add.
-   Step 3: git commit -m "<your message>"
-   Step 4: git git remote add origin https://github.com/{username}/{reponame}.git
-   Step 5: git push -u origin main
```
### 2.3. How to sync remote repo and local repo?
-   Step 1: git pull   
    🚨 You should pull before push to avoid the conflicts
### 2.4. How to work with branch?
    This is branch 
![git_branch](https://bkhost.vn/wp-content/uploads/2022/05/git-branches-merge.png)
```bash
-   Step 1: create new branch: git branch <branch name>
-   Step 2: switch branch: git checkout <branch name>
-   Step 3: see all branch in your repo: git branch
```
Or just: git checkout -b <branch name> to create and switch to the new branch
    ❓ So when you finish modify the new branch, you want to merge this branch to main(master), please do:
```bash
-   Step 1: git checkout master
-   Step 2: git merge <your branch name>
-   Step 3: git push 
```
    Now your Remote Repo is updated
### 2.5 git stash
The git stash command takes your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy, using:
 ```bash 
 git stash 
 ```
📦 After git stash one or more times, you can review the list of saved changes with the command: 
 ```bash 
 git stash list
 ```
📦 To view the content of each change:
 ```bash 
 git stash list -p
 ```
📦 To view the content of nth change:
 ```bash 
 git stash show stash@{n}
 ```
📦 To apply the nth change:
 ```bash 
 git stash apply stash@{n}
 ```   
# 📦 Some git popular commands
    -   init    
    -   add/ add.
    -   commit
    -   pull
    -   push
    -   clone
    -   log
    -   branch
    -   checkout
    -   merge
# 📥 Download
-   [Download for MacOS/Windows/Linux](https://git-scm.com/downloads)
-   [Documentation](https://git-scm.com/doc)

# 🧙‍♂️ Community

-   [Git Commmunity](https://git-scm.com/community)


