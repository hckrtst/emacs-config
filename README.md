# Emacs configuration

If .emacs.d exists then

```
cd .emacs.d
git init
git remote add src git@github.com:hckrtst/emacsd.git
git pull src

...make changes...

git push -u src master

```

You may see an error here, to merge prorperly do the following
and try again

```
git pull --allow-unrelated-histories src master

```
