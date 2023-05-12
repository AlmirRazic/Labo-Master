# Prerequisites

## Setting up/updating the git environment and git flow

[Get the installer](https://git-scm.com/downloads)

{% hint style="info" %}
Git-flow library:\
For Windows, is natively integrated.\
For Mac, [here is the procedure](https://git-scm.com/download/mac).\
Pour Linux, [here is the procedure.](https://howtoinstall.co/en/git-flow)
{% endhint %}

![image-20230509114028409](assets/image-20230509114028409.png)

* [ ] Confirm the installed version

```
[INPUT]
git version

[OUTPUT]
git version 2.40.1.windows.1
```

* [ ] What do you think about this release?

```
Git v2.40.1 Release Notes
=========================

This release merges up the fix that appears in v2.30.9, v2.31.8,
v2.32.7, v2.33.8, v2.34.8, v2.35.8, v2.36.6, v2.37.7, v2.38.5
and v2.39.3 to address the security issues CVE-2023-25652,
CVE-2023-25815, and CVE-2023-29007; see the release notes for these
versions for details.
```

## What's git-flow, branches feature.

[Source](https://nvie.com/posts/a-successful-git-branching-model/)

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Source : A successful git branching model</p></figcaption></figure>

* [ ] Which branches are persistent and what do they contain?

```
master and develop are persistent and they contains hotfixes, release branches and features branches.

sources:
image sur le gitbook et ChatGPT
```

* [ ] Why do we have to merge hotfix in both master and develop branches, but not into all active feature branches?

```
To ensure the stability and integrity of the codebase while minimizing disruption to ongoing feature development.
```

## Initialize git flow on an existing project

* [ ] What happens when you run the "git flow init" command on an existing local repository?

```
git flow init

Which branch should be used for bringing forth production releases?
   - main
Branch name for production releases: [main]
Branch name for "next release" development: [develop]

How to name your supporting branch prefixes?
Feature branches? [feature/]
Bugfix branches? [bugfix/]
Release branches? [release/]
Hotfix branches? [hotfix/]
Support branches? [support/]
Version tag prefix? []
Hooks and filters directory? [D:/GIT/Labo-Master/.git/hooks]
```

* [ ] When do we need to make this git command?

```
Setting Up a New Repository, When we start a new project or create a new repository
```

## Practice the basic git commands

[Source](https://www.atlassian.com/git/glossary)

* [ ] What does this git command "git add --all" achieve (.gitignore impacts)?

```
push everything
```

* [ ] What does this git command "git status" achieve?

```
git status
On branch develop
nothing to commit, working tree clean
```

* [ ] What does this git command "git remote add upstream \<url>" achieve?

```
This command establishes a connection to another Git repository
```
