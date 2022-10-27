# Getting to Know Git

To begin with, I took freeCodeCamp [Crash Course](https://youtu.be/RGOj5yH7evk). 

### What is git? 

Git is a version control system, it is a way to track your code changings by saving the initial coding, updating code and then have access all of the changes that had been made over time.
The difference between Git and GitHub is that the first one is a tool that track changes of code over time, as said before, and Github allows you to host your repositories online


### Git commands:

- ``` init```: turn an existing directory into a git repository
- ```clone```: bring a repository that is hosted somewhere else into your computer
- ```add```: get to know git that you had updated/delete file so it can update them
- ```commit```: save your files in git
- ```push```: upload your files to a remote repository
- ```pull```: bring changes that have been made on the remote repository to you local mahcine

*More commands can be found on this [page](https://training.github.com/downloads/github-git-cheat-sheet.pdf)*

### Git Branch

Git branches allow developers to diverge from the main branch by creating separate branches to isolate code changes, it means you diverge from the main line of development and continue to do work without messing with that master line. Having a branching strategy is necessary to avoid conflicts when merging and to allow for the easier integration of changes into the master trunk.

**Strategies:**
- GitFlow
- GitHubFlow
- GitLab Flow
- Trunk-based development

*Information about Branching strategies can be found [here](https://www.flagship.io/git-branching-strategies/)*

### Git tags and commits

Commits are the core building block units of a Git Project timeline, that can be thought of as the snapshot along the timeline.Meanwhile Git has the ability to tag specific points in a repository’s history as being important, allowing you to attach tags to commits so that you can refer to them in the future. 

*More information about [commits](https://www.atlassian.com/git/tutorials/saving-changes/git-commit#:~:text=Commits%20are%20the%20core%20building,at%20that%20point%20in%20time. 
) and [tags](https://git-scm.com/book/en/v2/Git-Basics-Tagging ).*

### Stash coommands and hooks

Stash means to store (changes) safely in a hidden place (the stash stack). Git hooks are scripts that run automatically every time a particular event occurs in a Git repository. 

*The information about stash and hooks was read from this pages: [freeCodeCamp]( https://www.freecodecamp.org/news/git-stash-commands/ ), [Atlassian - stash](https://www.atlassian.com/git/tutorials/saving-changes/git-stash), [Atlassina - hook](https://www.atlassian.com/git/tutorials/git-hooks )*

### Merge vs Reberge

Rebasing and merging are both designed to integrate changes from one branch into another branch but in different ways. On one hand, rerge preserves history whereas rebase rewrites it.

*Thse Study material was found from: [Atlassian](https://www.atlassian.com/git/tutorials/merging-vs-rebasing ), [Matt-rickard]( https://matt-rickard.com/squash-merge-or-rebase ) and [git-tower]( https://www.git-tower.com/learn/git/faq/git-squash)*

<sub>All the information that I found usefull and helpfull can be found [here](https://docs.google.com/document/d/1JkghbRDEKanaiZg2oTLlZaMN-Hyxu2ABhPuH6EOnFEg/edit?usp=sharing)</sub>
