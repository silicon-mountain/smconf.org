# Contributing to smconf.org 


## Issue Contributions

When opening new issues or commenting on existing issues on this repository
please make sure discussions are related to concrete technical issues and do so POLITELY.


## Code Contributions

The Silicon Mountain Community is open and always welcomes new contributors.
Individuals making significant and valuable contributions are made
_Collaborators_ and given commit-access to the project after successfully having a pull request reviewed and Merged.

This document will guide you through the contribution process.

### Step 1: Fork

Fork the project [on GitHub](https://github.com/silicon-mountain/smconf.org.git) and check out your
copy locally.

```text
$ git clone git@github.com:username/smconf.org.git
$ cd node
$ git remote add upstream git://github.com/silicon-mountain/smconf.org.git
```

#### Which branch?

For developing new features and bug fixes, the `master` branch should be pulled
and built upon.

### Step 2: Branch

Create a feature branch and start hacking:

```text
$ git checkout -b my-feature-branch -t origin/master
```
 A branch name should either reflect the issue being worked on or just use your first name.

### Step 3: Commit

Make sure git knows your name and email address:

```text
$ git config --global user.name "J. Random User"
$ git config --global user.email "j.random.user@example.com"
```

Writing good commit logs is important. A commit log should describe what
changed and why. Follow these guidelines when writing one:

1. The first line should be 50 characters or less and contain a short
   description of the change prefixed with the Issue number (e.g. "ISSUE 44: Created Contributing Document").
2. Keep the second line blank.
3. Wrap all other lines at 72 columns.

A good commit log can look something like this:

```
ISSUE 44: Added more info to the Contributors Guide.
```


### Step 4: Rebase

Use `git rebase` (not `git merge`) to sync your work from time to time.

```text
$ git fetch upstream
$ git rebase upstream/master
```



### Step 5: Push

```text
$ git push origin my-feature-branch
```

Go to https://github.com/yourusername/smconf.org and select your feature branch.
Click the 'Pull Request' button and fill out the form.

Pull requests are usually reviewed within a few days. If there are comments
to address, apply your changes in a separate commit and push that to your
feature branch. Post a comment in the pull request afterwards; GitHub does
not send out notifications when you add commits.

