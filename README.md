# Commit-Rule
My personal commit rule 

Last-maj : 04/09/19

### #1 

Use icons like [here](https://gitmoji.carloscuesta.me/)

### #2

Format your commit : 

```
:icon: type(scope) : subject
description
```

*Only icon, type and subject is obligatory*

Type is : 

#### dependencies, build system, integration
- ``build`` changes that affect the build system or external dependencies (npm, make ...)
- ``ci`` changes concerning the files and scripts of integration or configuration (Travis, Ansible, BrowserStack ...)

#### general
- ``feat`` adding a new feature
- ``fix`` fixed a bug
- ``perf`` performance improvement
- ``refactor`` change that does not bring new functionality or performance improvement
- ``style`` change that does not bring any functional or semantic alteration (indentation, formatting, addition of space, renaming of a variable ...)
- ``test`` adding or modifying tests

#### docs, git, bdd
- ``docs`` writing or updating documentation (readme.md and database.md)
- ``git`` adding or modifying .gitignore

Scope is a part of the project (like bdd, front, product, ....).

Subject is a short description of yours change.

Description is a long description of yours change.

### #3 

If you use another account than yours sign the commits
