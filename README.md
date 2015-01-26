Now supports Masonry!

gippy
=====

A single page web app to explore the latest python project code check-ins on GitHub. Also supports other languages like PHP. 

Why?
====

Because I like exploring GitHub

Future
======

- [x] Extend to work with other languages

Bugs
====

At first load, the repos come in top down, but subsequent ones get prepended, which causes the page to shift every time it loads new repos. This is ugly. 

Possible solutions - 

1. build the list bottom-up and append new repos to the bottom. OR 
2. figure out a way to prepend to the page without shifting the scroll location. 
