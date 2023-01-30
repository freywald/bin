
# Kommandozentrale

My shell scripts, including customized .bashrc with installer script.

> Not trash, but fash – for your bash only
>
> &mdash; <cite>Betris Baloa</cite>

## Example

![shell examples](https://github.com/freywald/bin/blob/master/documents/example.png?raw=true)

Format specification: ```'~'$USERNAME [if login type is 'remote', then: '🖧'] 'at' $HOSTNAME ['as' $CHROOT_MESSAGE] · [if command 'git' is available && $CURRENT_WORKING_PATH is a git repository, then: 'head' $HEAD_STATUS · $REPOSITORY_STATE] · 'Δs' $DELTA_TIME · 'at' $CURRENT_WORKING_PATH $END_SIGN```

## Installation (Five Step Exercise Human Evaluation Marathon)

1. ```$ git clone git@github.com:freywald/bin.git scripts && cd scripts && ./install```
   The scripts will be installed for the current user only. You may execute the install script again within *another* user context (yes – to install the scripts for the *other* active user – you're very, very smart). The old .bashrc and .bash_aliases – if existing within interpreted tilde character context – are backed up to your home directory. The tilde character looks like this **~**, please be aware of it for a few seconds, I hope you won't mind having it on your mind for a while, thanks, we know it's quite a burden, yes, we know it's hard, **sorry**. UwU, but you gotta keep it up, human.
2. You can delete the script folder which is created on git clone command during step 1 any time now if you're done. –– And you're done, as you should know.
3. You may need to relogin to see the new shell customization in action.
4. That was fun, right? UwU
5. 
