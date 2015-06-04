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

If you want emacs to run the server by default, uncomment the line in init.el containing "(server-start)".
