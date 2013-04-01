---
title: CSS Layout Testing Snippet
date: 2013-03-16 21:58 UTC
tags: snippet, code
---

_I recently shared this tip on coderwall:_

As a pixel perfectionist, I like knowing that my layout and elements are exactly as I imagine they should be. I usually find myself adding random red backgrounds to certain elements while I am building my layout. I found this snippet of code to be immensely useful while testing:

`* { background: rgba(1, 1, 1, 0.1); }`


Then just assign a div with lots of things in it with a class of `.testing`!