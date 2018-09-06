## git in bash

### show branch and git status

    source /usr/share/git-core/contrib/completion/git-prompt.sh
    PS1='\[\033[01;31m\]$(__git_ps1 "(%s)")\[\033[00m\]'$PS1
    GIT_PS1_SHOWUPSTREAM="auto"
    GIT_PS1_SHOWDIRTYSTATE="true"
    GIT_PS1_SHOWUNTRACKEDFILES="true"

### git alias

    [color]
            ui = true
    [core]
            pager = less
    [alias]
            co = checkout
            st = status
            di = diff
            ci = commit
            br = branch
            mt = mergetool
            sta = stash
            lg = log --graph --pretty=format:'%Cred%h%Creset%C(yellow)%d%Creset %s %Cgreen(%cr)%Creset%Cred(%an)%Creset' --abbrev-commit --date=relative

### git review

   add [remote "gerrit"]

### tobe continue
