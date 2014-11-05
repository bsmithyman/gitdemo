---
author: Brendan Smithyman
title: Git Demo
date: November 3, 2014
---

## Introduction

Git is a [revision control system](http://en.wikipedia.org/wiki/Revision_control) that makes it possible to keep track of changes to text files^[NB: Git can also keep track of binary files, but the storage and versioning of binary files is less efficient, since each update stores a new copy of the file.] and share those changes with others. This sort of system is most commonly used in software development.

## Rough examples

Here are some examples that might help you in getting started!

### Initializing a repository

![Creating a new repository in an empty directory](images/screenshot01.png)

![Creating a new file in the the project directory](images/screenshot02.png)

![Adding the new file to version control, showing the staged file, and committing the result](images/screenshot03.png)

### Adding new files and changes

![Creating some new files, listing the directory contents, and showing the status of the Git repository](images/screenshot04.png)

![Checking for changes in the repository's files](images/screenshot05.png)

![Trying to check differences in image files, adding the changes and new files to version control, committing the results](images/screenshot06.png)

### Atomic commits and selecting changes

![Several simultaneous changes; adding only some of the files to the staging area](images/screenshot07.png)

![Showing the differences in the document; there are two main sets of changes](images/screenshot08.png)

![Adding only the second change—this goes with the images—using interactive mode](images/screenshot09.png)

![Showing the changes that are staged and those that aren't; committing related changes](images/screenshot10.png)

![Showing the remaining changes that were not staged before](images/screenshot11.png)

![Adding the changes and committing](images/screenshot12.png)

### More changes, and showing logs

![Adding some more files](images/screenshot13.png)

![Showing the commit logs](images/screenshot14.png)

![Showing summary of the commit logs](images/screenshot15.png)

![Showing commit logs with decorations (branches, tags, etc.) and a straight-line graph](images/screenshot16.png)

### Branching and merging

![Creating a branch for improving links](images/screenshot17.png)

![Making changes in the new branch **improvelinks**](images/screenshot18.png)

![Back on the **master** branch, making some more changes](images/screenshot19.png)

![Making changes in a branch called **fixtypo**](images/screenshot20.png)

![Committing the changes to the fixtypo branch](images/screenshot21.png)

![Merging the **fixtypo** branch into **master** by "fast-forward"](images/screenshot22.png)

![Merging the **improvelinks** branch into **master** by "recursive"](images/screenshot23.png)

## Useful links

### Tutorials

- [tryGit][]
- [Atlassian Git Tutorials][AtlassianTutor]
- [Official Git Documentation][GitSCMDoc]

### Documents

- [Git Internals PDF][GitInternals]
- [Think Like (a) Git][TLaG]

### Talks

- [Git for ages 4 and up][4andUp]

### Hosting services

- [GitHub][]
- [BitBucket][]

[tryGit]: https://try.github.io
[AtlassianTutor]: https://www.atlassian.com/git/tutorials
[GitSCMDoc]: http://git-scm.com/doc
[GitInternals]: https://github.com/pluralsight/git-internals-pdf
[4andUp]: https://www.youtube.com/watch?v=1ffBJ4sVUb4
[TLaG]: http://think-like-a-git.net
[GitHub]: https://github.com
[BitBucket]: https://bitbucket.org
