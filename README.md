# sh-versioner

## Tested with
* sh-versioner v1.0.0
* osx 10.14
* make 3.81
* git 2.3.2

## How it works
The script's mechanics relies on git tags. It checks what are the differences between particular tags (newest and older one) and based on that generates changelog.

## How to install
For now it's just a demo that can be manually copied and pasted into any project. If the project contains already a makefile it's important to merge it's tasks with the sh-changelog tasks.

## How to use it
1. Make changes to the project you're working on
2. Commit in the changes
3. If your project is ready to be versioned use `$ make version V=v0.0.0` command
