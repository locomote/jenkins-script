jenkins-script
==============

Common jenkins build scripts, to be included as a submodule in other projects.

Usage:

```
cd PROJECT
git submodule add git@github.com:locomote/jenkins-script.git jenkins &&
git commit -m "Add jenkins submodule" &&
git push origin master
```

Then add the build step to the job in jenkins:

```
Command: jenkins/build
```
