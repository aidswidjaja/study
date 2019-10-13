---
title: "tree"
layout: default
nav_exclude: true
search_exclude: true
---

# tree


1. If you haven't got tree, get it!
    2. On Mac (using Homebrew):
    ```
    brew install tree
    ```
    2. On Debian (using APT):
    ```
    sudo apt-get install tree
    ```
1. cd (assuming in root directory):
```
cd study/docs/resources/maths/pracpapers
```
1. Run tree – is the output...?
    2. charset == UTF-8
    2. filename == index.html
    2. filetype == HTML
    2. JSON and XML will not work with Netlify/Apache/WEBrick for obvious reasons lol, so ensure filetype != JSON OR XML
```
tree -H '.' -L 1 --noreport --charset utf-8 > index.html
```
1. Push it to the Git repo (this section assumes you are still in `~/docs/resources/maths/pracpapers`):
```
git add *
git commit -m "Your commit message here"
git push origin master
```

