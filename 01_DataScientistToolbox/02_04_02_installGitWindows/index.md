---
title       : Install Git in Windows
subtitle    : 
author      : Jeffrey Leek
job         : Johns Hopkins Bloomberg School of Public Health
logo        : bloomberg_shield.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow   # 
url:
  lib: ../../libraries
  assets: ../../assets
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}

---

## Download Git

* Go to the following website and click on the Windows download link:

[http://git-scm.com/downloads](http://git-scm.com/downloads)

<img class=center src=../../assets/img/IntroToGit/gitDownload1.png height='350'/>

---

## Install Git

* Once the file is done downloading, open it up to begin the Git installation

<img class=center src=../../assets/img/IntroToGit/gitInstall1.png height='350'/>

---

## Install Git

* Unless you really know what you are doing, just go with the default options at each step of the installation

* Once the install is complete, hit the "Finish" button (you may want to uncheck the box next to "Review ReleaseNotes.rtf")

<img class=center src=../../assets/img/IntroToGit/gitInstall9.png height='350'/>

---

## Open Git Bash

* Find a program called Git Bash, which is the command line environment for interacting with Git
* It should be located in the Git directory within your Start Menu (or in the directory into which Git was installed)

<img class=center src=../../assets/img/IntroToGit/gitConfig1b.png height='350'/>

---

## Open Git Bash

* Once Git Bash opens, you'll see a short welcome message followed by the name of your computer and a dollar sign on the next line
* The dollar sign means that it's your turn to type a command

<img class=center src=../../assets/img/IntroToGit/gitOpen1.png width='750'/>

---

## Configure Username and Email

* Each commit to a Git repository will be "tagged" with the username of the person who made the commit
* Enter the following commands in Git Bash, one at a time, to set your username and email:

```
$ git config --global user.name "Your Name Here"
$ git config --global user.email "your_email@example.com"
```

* Make sure there are 2 dashes side-by-side before the word "global"
* You'll only have to do this once, but you can always change these down the road using the same commands

---

## Configure Username and Email

* Now type the following to confirm your changes (they may be listed toward the bottom):

```
$ git config --list
```

* Make sure there are 2 separate dashes (side-by-side) before the word "global"

<img class=center src=../../assets/img/IntroToGit/gitConfig2.png height='350'/>

---

## What's Next?

* Go ahead and close Git Bash with the following command:

```
$ exit
```

* Now that Git is set up on your computer, we're ready to move on to GitHub, which is a web-based platform that lets you do some pretty cool stuff
* Once GitHub is up and running, we'll show you how to start using these tools to your benefit
