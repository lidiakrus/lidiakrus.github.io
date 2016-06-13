---
layout: post
title:  "#cheatsheet Github + Jekyll"
date:   2015-09-05 13:46:24
categories: blog
lang: en
---

Serve Jekyll site locally the same way as on Github Pages

~~~~sh
$ cd .../username.github.io/
$ bundle exec jekyll serve 
~~~~

=> Browse to `http://localhost:4000`.

Other bundle commands:

`$ bundle update` - to ensure you always have an up-to-date system.


Push to Github

```sh
$ git status	# just for yourself to get an overview
$ git add -all 
$ git commit -m "initial commit"
$ git push -u origin master
```


Links: 
[Github Pages][url-ghpages],
[Jekyll home][url-jekyll], 
[Jekyll directory structure](https://jekyllrb.com/docs/structure/).

[url-jekyll]:       https://jekyllrb.com
[url-ghpages]:		https://pages.github.com