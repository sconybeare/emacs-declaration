Installation Instructions:
----------
```
git clone https://github.com/sebmathguy/emacs-declaration.git
mv .emacs.d .emacs.d.bak
cp . ~/.emacs.d
```

Open emacs. If you don't see el-get downloading lots of packages:

> mv .emacs .emacs.bak

If bootstrapping fails, you probably need to install automake and build-essential.

Emacs Server:
---------

If you don't have Inconsolata and you want to use emacsclient -c, then you need to either install inconsolata or comment out that line in init.el

If you want emacs to run the server by default, uncomment the line in init.el containing "(server-start)".
