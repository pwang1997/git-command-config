# git-command-config

#### Checking existing config
```
git config --global --list
```

#### Editing git config
```
git config --global --edit
```

#### Set git config
```
git config --global [
```

#### Here is some configs I am currently using:
```
# From git config --global --list
alias.co=checkout # git checkout => git co
alias.aa=add . # git add . => git add
alias.cam=commit --amend # git commit --amend "message" => git cam "message"
alias.cm=commit -m # git commit -m "message" => git cm "message"
alias.ss=status # git status => git ss
alias.cg=config --global git config --global => git cg
```

```
# From git config --global --edit
[alias]
        co = checkout
        aa = add .
        cam = commit --amend
        cm = commit -m
        ss = status
        cg = config --global
```
