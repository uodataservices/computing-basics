---
title: Current directory
layout: topic
order: 106
---

Also known as: "this directory" or "current working directory"

When you are navigating the file system the concept of _which directory you are
in_ is very important, especially when you are working on the
[command line]({{ site.baseurl }}/command-line). It's also essential when you need to import data into an R or Python script and then write it to a specific folder.

This matters because when you refer to files, by default the computer will
assume you're referring to files relative to where you are.

### Find out which directory you are in

From the command line, the `pwd` command (pwd is short for "print working directory") tells you where you are.

    pwd

> To find your (current) working directory in Python, use the `getcwd()` function from the `os` library: `import os` and `print(os.getcwd())`
>
> To find your (current) working directory in R, use the base command `getwd()`

### Change directory

To change into the directory `pictures` on the command line, do this:

    cd pictures

...but this will only work if the directory `pictures` is in the
current directory. If it isn't, you'll need to provide a 
[path]({{ site.baseurl }}/files/paths) to it.

> To change your (current) working directory in Python, use the same `os` library to change your path `os.chdir('[path]')` and then confirm the change with `print(os.getcwd())`.
> You can change working directory in R using `setwd('[path]')`. However, this can [cause problems when sharing scripts](https://swcarpentry.github.io/r-novice-inflammation/06-best-practices-R.html#be-careful-when-using-setwd), and in almost all circumstances you should instead [create an R project](https://swcarpentry.github.io/r-novice-gapminder/02-project-intro.html).