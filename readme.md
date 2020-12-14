<p align="center">
  
  <img src="https://i.imgur.com/1ElMTc2.png" alt="raven" width="400" height="400">

  <br>

  <a href="https://github.com/1pulse/factorio_biter_battles/issues?q=is%3Aopen+is%3Aissue">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/1pulse/factorio_biter_battles">
  </a>

  <a href="https://github.com/1pulse/factorio_biter_battles/issues?q=is%3Aissue+is%3Aclosed">
    <img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed-raw/1pulse/factorio_biter_battles">
  </a>

  <a href = "https://github.com/1pulse/factorio_biter_battles/pulls?q=is%3Aopen+is%3Apr">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr-raw/1pulse/factorio_biter_battles">
  </a>

  <a href = "https://github.com/1pulse/factorio_biter_battles/pulls?q=is%3Apr+is%3Aclosed">
    <img alt="GitHub closed pull requests" src="https://img.shields.io/github/issues-pr-closed-raw/1pulse/factorio_biter_battles">
  </a>

  <a>
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/1pulse/factorio_biter_battles">
  </a>

  <a href="https://discord.gg/zwtBDnSTS5">
    <img alt="Discord" src="https://img.shields.io/discord/662768298655744013">
  </a>
</p>

<br>

# Factorio Biter Battles
A team vs team factorio scenario. Duke it out on a mirrored map, advancing through technologies whilst fending off natural biters and those sent from the other team. This is a forked project of from [ComfyFactorio](https://github.com/M3wM3w/ComfyFactorio)

<br>

### Join the community
- We're live on [discord](https://discord.gg/fBKvBENj2d)!

<br>

### Learn how to play
- Multiple guides are avilable for viewing on our discord in the #learning channel, to help get you started on our servers. A few are listed below:
- [DashieCee's Biter Battle meta guide](https://pdfhost.io/v/t1vQW8ac5_Biter_Battles_Meta_Guidepdf.pdf)
<!-- Add the guides included in the in-game menu with the owner name, description of content etc -->

<br>

### Factorio Version
- The version used will tend to be the one used by the largest majority of the playerbase, to ensure that servers are always available to the most players. We are currently using stable 1.0.

<br>
<br>

---

## Contributing to the git repo
Many of the guides in the internet will probably explain it better e.g. https://guides.github.com/introduction/flow/

## I've set it up before
Run the following to create a new branch and make changes as usual: 
-  ```git fetch```
- ```git checkout master``` - switch to master
- ```git reset origin/master``` - update your local copy of master to match github
- ```git clean -f```
- ```git branch <new branch>```
- ```git checkout <new branch>```

## I'm setting it up for the first time

### Create a fork 
Go to https://github.com/1pulse/factorio_biter_battles, then click fork. 

### Clone the repo
- Go to your factorio scenarios folder (try %APPDATA%/roaming/factorio/scenarios)
- Run ```git clone <repo>```

repo is the url of your fork which you can get from the green ```Code``` button in github.

>You may want to change the name of the folder that resulted from git clone. 
><br>To test changes, create a new game using the scenario whose name matches the folder name generated by the git clone. 

### Check your remote settings

Run ``` git remote show origin ``` which would show something like this
<br>This uses SSH version which assumes that you have [ssh keys setup](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/connecting-to-github-with-ssh). 
<br>The https urls should still work. 
  
```  
  Fetch URL: git@github.com:1pulse/factorio_biter_battles.git
  Push  URL: git@github.com:<your fork>
```

If it's not like the above:

Set the fetch url 
```
git remote set-url origin git@github.com:1pulse/factorio_biter_battles.git
```
Set the push url 
```
git remote set-url origin -push <your repo>
```

---
## Branching
Create a branch: ``` git branch <branch name> ```

Switch to your branch: ```git checkout <branch name> ``` 

>Branches are a snapshot in time. You can break it as much as you want and can still switch to the original branch which is usually named either ```master``` or ```main```. You can also have multiple branches at the same time.

### Make your changes
Make your changes using your favourite editor
- To see the list of files that you've changed: ```git status```
- To see the changes you've made: ```git diff``` or ```git diff <filename>```

Stage your changes: run ```git add <filename>``` or ```git add . ```(to add all files with unstaged changes)

Commit your changes: run ```git commit -m <your custom commit message>``` 

### Submit a pull request
Once you are happy with your changes: run ```git push```
This will send the changes in your local branch to your branch in github. 

In github, click ```Pull Request```
- base repository: ```1pulse/factorio_biter_battles```
- base: ``master``
- head repository: ``` your repo```
- compare: ```your branch```
