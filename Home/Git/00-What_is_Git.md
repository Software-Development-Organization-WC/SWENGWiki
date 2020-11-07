# What is Git?

***Git*** is an open-source version control software. This type of software allows developers, either on their own or in a team, more easily track changes, merge code, and maintain the history of files in a project.

## How does it work?

This question doesn't have a very straightforward answer as Git is a complex piece of software. Luckily, the beginner Git user does not need to know every detail to get started. The fundamentals are as follows:

### Repositories

A Git ***repository*** can be thought of the directory at the top of a project that contains all of the files and subdirectory hierarchy that forms the project. This wiki comes in the form of a Git repository.

### Commits

A ***commit*** represents a "snapshot" in time of the repository and all of it's contents (except those ignored due to the **.gitignore** file). The developer has full control over when and how commits are made. It's good practice to include a descriptive message with each commit describing the purpose of the changes made since the last commit. It's also a good idea to only have related changes in a single commit. In other words, it's generally bad practice to make a lot of changes that aren't related to each other and track them in a single commit. This comes at the discretion of the developer and is highly subjective, but practice and self-discipline go a long way.

### Branches

A ***branch*** represents a version of the repository which allows for non-linear development of a project. Generally the default branch is considered the "release" branch (usually called "master," "main," or similar), which is ideally the most stable and free from bugs. There can be many different branches, so that features and bug fixes in-progress on a "non-master" branch have no threat to the stability of the code in the master branch. Once a "non-master" branch has been developed to the point of being stable and has been thoroughly tested, it can be merged into another branch to bring in the new changes. For example, a "develop" branch could be used to write new features until they are complete and free from bugs, and then merged into "master" to become part of the stable branch. Git automatically handles the differences between the the code in the two seperate branches and is typically able to determine on it's own how to splice the code together.

Occasionally, and for various reasons, Git will be unable to determine how to splice changes in between branches and "merge conflicts" can occur. This requires the developer to manually identify whether to use the incoming changes (from the branch being merged from), or the current changes (from the branch being merged to).

### .gitignore

The ***.gitignore*** file lives at the top level of a repository and tells Git what files to consider as relevant to the repository, and therefore which changes to track or ignore in a commit. If this file doesn't exist, then Git will not ignore any files in the repository.

## Should I use Git?

Git certainly isn't the only choice in version control software, but it is likely the most popular and has a large community of experienced users, so it's probably the easiest to get started with. All developers should consider implementing some form of version control software into their workflows and Git is a great choice. Very many companies across a vast range of industries use Git, and a potential employer might be impressed by an applicant's pre-existing experience with Git, even if only in an academic setting.