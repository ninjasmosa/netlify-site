---
title: "He/She to They userscript"
description: "Userscript to turn any instance of 'He/She' on a web page to 'They'"
date: 2022-08-13
tags: 
    - projects
    - userscript
    - javascript
categories:
    - Projects
draft: false
---

## What is it?
This is a userscript that replaces any instance of "He/She" or "He or She" on a web page to "They". The code can recognise instances of "he/she is" and replace them with "they are" to maintain grammatical correctness. Other contextual differences can be recognised and replaced accordingly.

## How do I use this?
You will need a userscript manager. I recommend [Tampermonkey](https://www.tampermonkey.net).

Once you have Tampermonkey installed, [visit the GitHub repo](https://github.com/ninjasmosa/He-She-to-They) and follow the instructions in the readme.

## This extension is unfinished
There may be rough edges and instances where this extension many not work. If that this is the case, either [create an issue](https://github.com/ninjasmosa/He-She-to-They-/issues) or [submit a pull request](https://github.com/ninjasmosa/He-She-to-They-/pulls) with edited code.

## See the script in action
[This debug video](https://user-images.githubusercontent.com/27077617/184457771-afeb96df-b642-40c5-a2cd-6af3acc4dc11.mp4) should give you a general idea on what this extension does. However it may not accurately represent normal usage.

## Known issues
[The script doesn't function correctly at all if a string in the body contains any capitalisation](https://github.com/ninjasmosa/He-She-to-They/issues/1)