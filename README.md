![image](https://user-images.githubusercontent.com/70385488/192114009-0830321a-d227-4a4d-8411-6c03b54d7ce6.png)

HACKTOBERFEST IS DIGITALOCEAN’S ANNUAL EVENT THAT ENCOURAGES PEOPLE TO CONTRIBUTE TO OPEN SOURCE THROUGHOUT OCTOBER. MUCH OF MODERN TECH INFRASTRUCTURE—INCLUDING SOME OF DIGITALOCEAN’S OWN PRODUCTS—RELIES ON OPEN-SOURCE PROJECTS BUILT AND MAINTAINED BY PASSIONATE PEOPLE WHO OFTEN DON’T HAVE THE STAFF OR BUDGETS TO DO MUCH MORE THAN KEEP THE PROJECT ALIVE. HACKTOBERFEST IS ALL ABOUT GIVING BACK TO THOSE PROJECTS, SHARPENING SKILLS, AND CELEBRATING ALL THINGS OPEN SOURCE, ESPECIALLY THE PEOPLE THAT MAKE OPEN SOURCE SO SPECIAL.
<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Getting Started](#getting-started)
* [Built With](#built-with)
* [Prerequisites](#prerequisites)
* [Installation](#installation)



<!-- ABOUT THE PROJECT
## About The Project
It is an e-commerce website whose name has totally not been stolen from somewhere else. It is a front-end based project where the participants will learn styling of pages, html and css features etc. It has been made using Html and Css.

Project Name - Vbay
-->

### Built With

* Html
* CSS


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.


### Installation

1. Clone the repo
```sh
git clone https://github.com/csivitu/vbay/
```
2. Start a new branch.
```sh
Check Contributing topic to find out about branching
```

3. And start your contributions.


### Prerequisites

HTML - https://youtu.be/Ut4RpySLM6Y

CSS  - https://youtu.be/1PnVor36_40


----------

## Steps to follow :scroll:

### Tip : Complete this process in GitHub (in your browser)

```mermaid
flowchart LR
    Fork[Fork the project]-->branch[Create a New Branch]
    branch-->Edit[Edit file]
    Edit-->commit[Commit the changes]
    commit -->|Finally|creatpr((Create a Pull Request))

 ```

### 0. Star The Repository :star2:

Star the repository by pressing the topmost-right button to start your wonderful journey.

### 1. Fork it :fork_and_knife:

You can get your own fork/copy of [HacktoberFest-2022](https://github.com/Open-Source-you/Hackotberfest2022 by using the <a href="https://github.com/Open-Source-you/HacktoberFest2022/new/master?readme=1#fork-destination-box"><kbd><b>Fork</b></kbd></a> button.


### 2. Clone it :busts_in_silhouette:

`NOTE: commands are to be executed on Linux, Mac, and Windows(using Powershell)`

You need to clone or (download) it to local machine using

```sh
$ git clone https://github.com/Open-Source-you/Hackotberfest2022.git
```

> This makes a local copy of the repository in your machine.
Once you have cloned the `Hacktoberfest-2022` repository in Github, move to that folder first using change directory command on Linux, Mac, and Windows(PowerShell to be used).

```sh
# This will change directory to a folder Hacktoberfest-2022
$ cd Hackotberfest2022
```

Move to this folder for all other commands.

### 3. Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/Hacktoberfest-2022.git (fetch)
origin  https://github.com/Your_Username/Hacktoberfest-2022.git (push)
```

Now, let's add a reference to the original [Hacktoberfest-2022]https://github.com/Open-Source-you/Hackotberfest2022) repository using


### 4. Sync it :recycle:

Always keep your local copy of the repository updated with the original repository.
Before making any changes and/or in an appropriate interval, run the following commands *carefully* to update your local repository.

```sh
# Fetch all remote repositories and delete any deleted remote branches
$ git fetch --all --prune
# Switch to `main` branch
$ git checkout main
# Reset local `main` branch to match the `upstream` repository's `main` branch
$ git reset --hard upstream/main
# Push changes to your forked `Hacktoberfest-2021` repo
$ git push origin main
```


### 5. Create a new branch :bangbang:

Whenever you are going to contribute. Please create a separate branch using command and keep your `main` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b BranchName
```

Create a separate branch for contribution and try to use the same name of the branch as of folder.

To switch to the desired branch

```sh
# To switch from one folder to other
$ git checkout BranchName
```

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add .
```

Type in a message relevant for the code reviewer using

```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin BranchName
```
