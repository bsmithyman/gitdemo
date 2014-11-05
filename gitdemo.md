---
author: Brendan Smithyman
title: Git Demo
date: November 3, 2014
---

## Introduction

Git is a [revision control system](http://en.wikipedia.org/wiki/Revision_control) that makes it possible to keep track of changes to text files^[NB: Git can also keep track of binary files, but the storage and versioning of binary files is less efficient, since each update stores a new copy of the file.] and share those changes with others. This sort of system is most commonly used in software development.

## Step-by-step guide

### Initializing a repository

![Creating a new repository in an empty directory](images/screenshot01.tiff)

![Creating a new file in the the project directory](images/screenshot02.tiff)

![Adding the new file to version control, showing the staged file, and committing the result](images/screenshot03.tiff)

### Adding new files and changes

![Creating some new files, listing the directory contents, and showing the status of the Git repository](images/screenshot04.tiff)

![Checking for changes in the repository's files](images/screenshot05.tiff)

![Trying to check differences in image files, adding the changes and new files to version control, committing the results](images/screenshot06.tiff)

### Atomic commits and selecting changes

![Several simultaneous changes; adding only some of the files to the staging area](images/screenshot07.tiff)

![Showing the differences in the document; there are two main sets of changes](images/screenshot08.tiff)

![Adding only the second change—this goes with the images—using interactive mode](images/screenshot09.tiff)

![Showing the changes that are staged and those that aren't; committing related changes](images/screenshot10.tiff)

![Showing the remaining changes that were not staged before](images/screenshot11.tiff)

![Adding the changes and committing](images/screenshot12.tiff)

### More changes, and showing logs

![Adding some more files](images/screenshot13.tiff)

![Showing the commit logs](images/screenshot14.tiff)

![Showing summary of the commit logs](images/screenshot15.tiff)

![Showing commit logs with decorations (branches, tags, etc.) and a straight-line graph](images/screenshot16.tiff)

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