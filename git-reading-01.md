# This is what I learned in the form of my notes about the Git Reading

### [Main Page](https://pale-crusader.github.io/learning-journal)

## Bullet points

* Essentially the term _"version control"_ is all about keeping track and accountability of changes, also being able to roll back changes, all the while being resource effecient  
* Localization is about being able to get the project (its repositories) on your machine so you can work on it
* Centralization is about having the the project (its repositories) in a place it can be accessed by multiple people so <Centralized Version Control System> was made. That was a single server which held the project.
* <Distributed Version Control systems> Came into being in part to midigate the threat of centralized failure causing the loss of everything. It works via mirroring.

### Git is a Distributed Version Control system which  
* Allows local operations
* Tracks changes
* Helps prevent loss of data

### Git works in stages
1. Committed
2. Modified
3. Staged

Which means first it is stored, then the change is made until finally the version is commited to the next snapshot

When Git is installed as part of a IDE it interacts with multiple softwares and can even access GitHub if so configured (and it commonly is)

Git has mandatory configuration, such as putting in a name and email to mark version changes with.

Many of the Terminal Commands you'll see in my [Text Editor and Terminal](https://pale-crusader.github.io/learning-journal/text-editor) page are git commands, not to mention my [git-demo](https://pale-crusader.github.io/learning-journal/git-demo) page. I hope to add more as we go.

When working locally there are three components

1. Working Directory
2. Index  
3. Head

Which are the where actual files reside, the area used for staging, and finally the thing which points to the most recent commit.

After you modify a file within the git repository it is tagged as modified, then with command you can stage it to modify which and then use another command to commit the change.

```git status``` is a command which allows you to check this pending and staged items

There are a list of commands you can also see on my [git-demo](https://pale-crusader.github.io/learning-journal/git-demo) page.

The Artle also talks about cloning which is a command which copy a repository wholecloth locally. If you already have the reposity and just want the changes you'd either fetch or pull (pulling fetches and merges)

### Remotes are the collaborators, by username

## Git has many ways to undo actions

* ```git commit --amend``` allow adding a message to a commit
* ```git reset HEAD``` allow unstaging a file
* ```git checkout --``` allow unmodifying a file

Branching is essential making alternative versions which may be worked on separately and then later merged

Merging is about taking tags from one version and putting them together with another.

Merging can be done a few ways and has the risk of having a conflict which may take comunication with collaborator(s).

rebasing is an alternative to merging and basically goes back to the common ancestor and works in both sets of changes which basicaly rewrites the project's history

Tags can be used in git to denote important milestones in the project


These are additional links

> http://git-scm.com  
https://github.com/  
https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf  
http://alx.github.io/gitbook/  
https://progit.org/  
https://blog.udemy.com/git-tutorial-a-comprehensive-guide/