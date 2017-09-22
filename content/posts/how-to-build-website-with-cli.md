---
title: "How to Build a website with CLI"
date: 2017-09-18T17:49:11+01:00
draft: false
---

This website is build in 3 minutes by CLI only. And it's really easy.

### 1. Requirement ###

* [git](https://git-scm.com)
* [hugo](https://gohugo.io/)
* Text editor (ie: nano)


### 2. How TO ###

First of all, 'hugo' is a static site generator. The content is will be converted from markdown to html.

The fist command will generate the basic site stucture:

`hugo new site yourSite`


Choose your hugo [theme](https://themes.gohugo.io) or build your own.
Add some config by editing `config.toml`

then, start your dev server

`hugo server -D`

The server will start in watch mode. it means the browser will refresh when you edit your files.


You can now add some content by executing this commande:

`hugo new posts/hello-world.md`

this will create a file under content folder, as you name it. In this cas, it will be 'content/posts/hello-world.md'.


 if you want to build your HTML version of your website execute:

 `hugo server -wDs path/of/dev-folder -d path/of/prod-folder`

 Finnaly just execute `hugo`. This will build your website inside public directory. Now you're ready :)


 That's it. Now you have a website. You can push the your username.github.io ot other hosting service.
