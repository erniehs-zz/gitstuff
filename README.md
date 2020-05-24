# gitstuff
general git and git related stuff i forget a lot because i'm lasy like that...

## log

https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History

## alias

https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases

```shell
git config --global alias.logline 'log --pretty=oneline --graph'
```

## ssh

https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

```shell

ssh-keygen -t rsa -b 4096 -C "ernie_hs@hotmail.com"

eval $(ssh-agent -s)

ssh-add ~/.ssh/id_rsa
```

## reset origin

https://help.github.com/en/github/using-git/changing-a-remotes-url

```shell
git remote remove origin

git remote add origin https://github.com/erniehs/boats.git

git push --set-upstream origin master
```
