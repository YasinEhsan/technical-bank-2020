# Notes

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Notes](#notes)
	- [clone 101](#clone-101)
	- [merge conflicts locally](#merge-conflicts-locally)
	- [merge conflicts with other branch](#merge-conflicts-with-other-branch)
	- [branching (detached head)](#branching-detached-head)
	- [general](#general)
	- [Markdown Hacks](#markdown-hacks)
	- [npm running server](#npm-running-server)
	- [Terminal 101](#terminal-101)
	- [Atom general](#atom-general)
	- [Atom markdown](#atom-markdown)
	- [Atom terminal](#atom-terminal)
	- [Links](#links)

<!-- /TOC -->


---
## clone 101
- git clone (paste ssh)
- git add .
- git commit
- git push

## merge conflicts locally
- git fetch
- git add .
- git commit
- git pull (resolve confilcts here)
- git push

## merge conflicts with other branch
- git branch
- git checkout (update branch name i.e. master)
- git merge (current branch name?)
- git push


## branching (detached head)
1. git branch -a
2. git checkout *branch name*
3. git add .
4. git commit -m ""
5. git push **OR...** git push upstream *branch name

## general
1. git status
2. git log -3 //past three commits


## Markdown Hacks
- Links types: Section, project file, href
- three backtics for code
- blockqoute with arrow
- emphasize with bold + cap

## npm running server
1. npm i (downloads new pack)
2. npm run dev
3. copy http link localhost
4. ctrl C
5. OR Python -m SimpleHTTPServer 8000

## Terminal 101
1. mv old-name new-name (Rename)
2. rm (delete file permanently)
3. rm -rf (delete folder permanently)

## Atom general
1. cmd shift p (Search)
2.

## Atom markdown
1. ctrl opt c (toggle first, then add TOC)
2. ctrl shift m (run markdown)
3. ctrl op r (remove TOC)

## Atom terminal
1. ctrl tilda key (open terminal)
2. cmd shift T (new terminal)
3. cmd option F (terminal focus)
4. cmd shift x (delete terminal)
5. cmd shift k (switch terminal)


## Links
- [Markdown Notes](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Notes")
- [Github Notes Mac](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf "Github Notes")