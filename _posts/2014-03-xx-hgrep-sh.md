---
layout: post
title: "egrep.sh"
published: true
date: 2014-03-02
comments: true

---

Here is a little script that highlights multiple egrep search terms in different colors. It pipes multiple greps together. Be careful, if you give it a search term that happens to match the escape sequences for ANSI color, you might get unexpected results.

There are a number of tools that already do this: [ack](http://beyondgrep.com/), [ccze](https://github.com/cornet/ccze). This just needs bash (maybe even other shells) and grep. I was aiming for portability; no need for compiling, perl, ruby, python, <insert runtime here> ... Got the idea [here](http://stackoverflow.com/questions/17236005/grep-output-with-multiple-colors).