# git-push-checker

A program that keeps me from commiting and pushing on master.

Sometimes I try small things on master/develop before I create branches to implement features. Especially in bigger teams and if we use systems like github it is an issue to push on master. I commit and push often so it happens I do it without realising I am working on master.

This program aks every time I try to push or commit if I really want to do it.


It is written for and tested in zsh only and meant to be sourced. Please check bash compatibility before trying it out.

Include it in .zshrc using `source path/to/git-push-checker`
