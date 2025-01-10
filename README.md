# Maven Flow Demo Library Project

This project demonstrates the common problems you will encounter when developing Maven applications with [GIT Flow](https://nvie.com/posts/a-successful-git-branching-model/) and how they can be resolved using components of [Maven Flow](https://github.com/maven-flow).

It is a small Java library managed by Maven with configured GitHub workflows that use Maven Flow components.

## Features

- Automatic prevention of Maven artifact overwrites from feature branches.
- Automatic merge conflict resolution in changelogs and maven artifact versions.
- Automatic merging of changes from `develop` branch into open pull requests.
- Automatic merging of bug fixes from feature branches into `develop` branch.

## Demonstrations

The following demonstrations make use of this project:

- [Fix Common Merging Issues in GIT Flow](https://www.jardoapps.com/fix-common-merging-issues-in-git-flow/)
- [Fix Maven Artifact Version Conflicts](https://www.jardoapps.com/fix-maven-artifact-version-conflicts/)

