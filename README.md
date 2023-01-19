# Jekyll new post bash script

Simple bash script to generate new Jekyll blog posts from command line

Original implementation: [this Gist](https://gist.github.com/aamnah/f89fca7906f66f6f6a12?permalink_comment_id=3243700#gistcomment-3243700)

## Usage

`new_post.sh Super interesting Post` will create `_posts/2023-01-19-super-interesting-post.md` (2023-01-19 will be replaced by current date) with this content:

```
---
title: "Super interesting Post"
date: 2023-01-19
tags: []
---
```

## Why ?

Unfortunately something prevented me from using [Jekyll-compose](https://github.com/jekyll/jekyll-compose); and I didn't have time to look deeply.
