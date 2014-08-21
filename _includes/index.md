Introduction
-------

This is a project (Projet in Français) about how to build a website.
This project is based on:

+ Jekyll
+ Github
+ Markdown
+ Html5 and CSS3

Editor and Image Tools
------------------------

Domain Name
------

1. Register in [www.dot.tk](http://www.dot.tk)
2. Search and register a free domain name ([projetcompromis.tk](http://projetcompromis.tk) for example).
3. Config the DNS (A and CNAME)

>      A 192.30.252.153<br/>
>      A 192.30.252.154<br/>
>      www CNAME QUXIAOFENG.GITHUB.IO<br/>

![](/images/dnsconfig.png)

##### CNAME

>    projetcompromis.tk


Git and Github Config
----------------

1. Register a Github Account
2. Install Git, generate a SSH key, copy the SSH key to your Github account, and set global settings
3. Clone a jekyll site in git bash
4. Edit all files
5. Remove the old git repo by `rm .git -rf` in the local git folder
6. Initial the new git repo by `git init` in the local git folder
7. Create `gh-pages` as the default branch by `git checkout -b gh-pages` in the local git folder
8. Create a new Github repo in the Github webpage. For example: [`projetcompromis`](https://github.com/quxiaofeng/projetcompromis) (Project Compromise in French)
9. Add the remote address to local git repo by `git remote add origin git@github.com:quxiaofeng/projetcompromis.git` in the local git folder
10. Add all files, commit changes and push to the remote by `git add -A && git commit -sm 'git init the website' && git push -u origin gh-pages`

###### Then we finished the first site.

After each modification, just add, commit, and push like this

      git add -A && git commit -sm 'WHAT-YOU-HAVE-DONE' && git push

Github Flavored Markdown
----------------

HTML5 and CCS
----------------

Design Concept
----------------

Templates and Examples
----------------

TODOs
------------


