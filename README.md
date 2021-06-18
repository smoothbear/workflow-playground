![banner](assets/banner.png)
## Workflow Playground

### Contents
* [Introduction](#Introduction)
* [Playground List](#Playground-List)
* [How to test workflows in local](#How-to-test-workflows-in-local)
* Issue
-----
### Introduction
* This repository is to practice [Github Workflow](https://docs.github.com/en/actions) patterns.
-----
### Playground List
* [1. Basic concepts](https://github.com/smoothbear/workflow-playground/tree/main/1.%20Basic%20concepts)
-----
### How to test workflows in local
Install [nektos/act](https://github.com/nektos/act) for testing.
<br/>
* Mac
```shell
brew install act
```
* Linux
```shell
curl https://raw.githubusercontent.com/nektos/act/master/install.sh | sudo bash
```
* Windows
```powershell
choco install act-cli
```
or using scoop
```powershell
scoop install act
```

Run workflows by using act
* Write workflows in .github/workflows
* Run below command
```shell
act -j <workflow job name>
```