## change history

```
if [ "$PROMPT_COMMAND" != "history -a" ];then
        if [  -f ~/.bash_history ];then
                export PROMPT_COMMAND="history -a"
                export HISTSIZE=3000
                export HISTTIMEFORMAT='%F %T '
        fi
        unset HISTCONTROL
fi
```

    HISTSIZE=1000000
    HISTFILESIZE=20000

## some more ls aliases

    alias ls='ls --color=auto'
    alias ll='ls -l'
    alias la='ls -A'
    alias l='ls -CF'
    alias rm='rm -i'
    alias mv='mv -i'
    alias cp='cp -i'
    alias pssh="parallel-ssh -p 30 -t 0"

## 
