
### Git is a distributed version control system

* Allows multiple developers to work on he same code
* Keeps history of changes and can view review, apply and remove changes
* Snapshots in time is a Commit, and each represents a change and equivalent to a _"Save As"_
* Saving multiple docs is wasteful due to Git saving the changes without re-saving the entire thing
* Each Commit has a hash code, and can have a message assigned to Commit
* The HEAD moves along with successive Commits, each being a revised Version
* The HEAD is
* __With Every Commit leave a Message!__

### [Main Page](https://pale-crusader.github.io/learning-journal)

### GitHub

* Is a Centralized online place to store and work on code together
* Keeps History like Git
* Keeps changes separate until approved by team and merge
* Can push and pull changes using Git

### Repository

* Usually 1 project = 1 Repository
* Really Large Projects with front and back ends may have multiple Repositories


## Git Workflow


1. __Add__ ie ```git add .```
2. __Commit__ ie ```git commit -m "putcomment in these quotes"```
3. __Push__ ie ```git push origin +master```

Adding is _NOT_ Commit! It is staging them to be commited

Git Pull pulls and merges it locally.

During a merge conflict you'll need to