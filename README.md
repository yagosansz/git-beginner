# Git & GitHub - Rocketseat

A practical guide for beginners.
(Someone changed this, *do not delete* !)

What is Git?

`A developer has the same powers as Thanos when he gets the time Stone!`

### Installation

https://git-scm.com/downloads

https://cmder.net/ full version for windows comes with Git =)

# Use-cases

- [x] You wish to create a timeline to keep track of your project development.
- [x] You wish to verify the changes made in your project.

- [x] Your want to add a new functionality to your project, without ruining what has already been developed.
- [x] You add the new functionalities to your project in production.
- [x] You want to delete the branch that has the newly added functionality, after having applied it in your project.

- [x] Upload your project to a remote repository (e.g.: GitHub).

- [x] You need clone a project that is in development.
- [x] You have to solve a conflict.
- [x] You have to update your local repository before uploading your changes to the remote repository.

- [x] You need to retrieve a file from a previous commit to your timeline.
- [x] You need to retrieve a file that was deleted.

# Commands learned

* `git init` \\ starts your project's timeline
* `git add` \\ adds or updates changes that are ready to go to the project's timeline
* `git commit` \\ adds changes to the project's timeline
* `git log` \\ shows changes that have been added to the project's timeline / commit
* `git status` \\  displays your project's change(s) status
* `git show` \\ displays specific events / commits of your timeline
* `git branch`  \\ manages your project's branches
* `git branch -D` \\ deletes a branch from your project
* `git checkout` \\ controls your timeline (e.g.: move between branches)
* `git checkout -b` \\ creates a branch and switches to it
* `git checkout <commit_code> -- <file_name>` \\ recovers a file from a specific commit in your timeline
* `git checkout -- <file_name>` \\ recovers a file (e.g.: deleted file) from latest commit
* `git merge` \\ combines different timelines / branches
* `git remote -v` \\ check your remote repositories
* `git push` \\ pushes changes from local repository to remote repository
* `git push -u origin master` \\ creates master branch in remote repository when pushing for the 1st time
* `git clone` \\ clone a project / repository
* `git pull` \\  pull files from remote repository to update local repository
