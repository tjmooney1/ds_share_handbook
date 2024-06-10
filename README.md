# DS at SHARE Handbook

The purpose of this handbook is to enable any new DS starter or curious analyst to be able to understand what the DS team do at a high level, and secondly, execute what we do.

This will be a living document, that will start very skeletonesque and narrow, before developing into something much more fleshed out and useful.

https://jamiehshare.github.io/ds_share_handbook/

# Contributing to the handbook

The handbook is written with [Quarto](https://quarto.org/docs/books/) which makes publishing seamless, and has fast become our go-to resource for literate programming.

The first step is to clone the repo - we find this easiest in the terminal, but you could also use the GitHub Desktop application or any software you're comfortable with.

> It will usually be helpful to have a 'git_repos' folder at your home directory, which you can access in the terminal via ~/git_repos. To make this directory, open up a terminal and type `mkdir ~/git_repos`.

Provided you have a 'git_repos' folder at your home directory you can clone the repo with the following commands:
`cd ~/git_repos`
`git clone https://github.com/jamiehshare/ds_share_handbook.git` 

Now you'll want to open up your RStudio IDE, `File` -> `New Project...` -> `Existing Directory` -->  `~/git_repos/ds_share_handbook`

This will load a project at the correct location, to preview the current state of the book open up the RStudio terminal and type `quarto preview`, this will open up a rendered version of the document in a browser. The documented will auto update as you save changes.

Now is a good idea to follow git best practices and create a fork rather than committing your changes directly to master/.

> Some projects use the master/ directory and others use main/

If I wanted to create a new branch called 'dev' I would type `git checkout -b "dev"` in the RStudio terminal. My IDE would then switch to the dev branch, and I can commit my changes to dev and merge with main later.




