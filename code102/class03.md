# Class 3

[Journal Home](README.md)  

Current Reading:

[Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Reading Notes: Gettting the Gist of Git

### Version Control

Local -> Centralized -> Dsitributed -> Git

The above is the chronological flow of the ideas that led to Git from programmers storing previous versions of code on their own hard disks. Distributed version control systems are the most modern and secure ways to insure that code will be protected from loss. A *mirrored* repositroy allows for two secure storage locations for projects.

### Git

The current longevity of Git is a huge advantage. Because so many programmers already use the Git ecosystem, you can be confident that what you are learning and becoming familiar with will be applicable through at least the beginning to intermediate portion of your career.

One can follow how to download Git by looking at this [webpage](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/).

Note that there are different instructions for different operating systems.

The initialization process listed is different than using GitHub as the source of creating a repository. The cloning process, however, is the same but the URL is not the one copied from GitHub.

Working directory is the area where the files for a website or project exists. This files are being tracked in Git and will save updates in the repository after the ACP process. Then the information in `add` to index. Index is the staging location, which I don't know what this means. The final step is the `commit` to the head. This is the process of pointing to the most recent commit in the repository.

In the tracking and staging subsection, the article points out that one can add *All Filies* if you use:

> git add *

which is different than whan we have uses:
> git add .

I don't know the difference between these two, if there is one.

You can use `git stash` to store changes with commiting them.

&copy; 2022, NoMichi
