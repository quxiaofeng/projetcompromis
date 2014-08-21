Introduction
-------

This is a project ("**Projet Compromis**" is "*Project Compromise*" in Français) about how to build a website.
This project is based on:

+ [Jekyll](http://jekyllrb.com/)
+ [Github](https://github.com/)
+ Markdown
+ Html5 and CSS3

Editor and Image Tools
------------------------

1. [Chrome](https://www.google.com/chrome/browser/)
1. [Sublime Text](http://www.sublimetext.com/)
2. [MarkdownPad](http://markdownpad.com/)
3. [Imagemagick](http://www.imagemagick.org/)

### [Chrome](https://www.google.com/chrome/browser/) 

This is the best browser for website designers. 

Press `Ctrl+Shift+I` shortcut or `F12` to open **Developer Tools**.

### [Sublime Text](http://www.sublimetext.com/)

Download [win64](http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%20Build%203059%20x64%20Setup.exe), [win32](http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%20Build%203059%20Setup.exe)

Best text editor.

### [MarkdownPad](http://markdownpad.com/)

[Download](http://markdownpad.com/download/markdownpad2-setup.exe)

A professional Markdown editor supporting local rendering.

### [Imagemagick](http://www.imagemagick.org/)

[Download](http://www.imagemagick.org/download/binaries/ImageMagick-6.8.9-7-Q16-x64-dll.exe)

A Professional Image Processing Library


Domain Name
------

1. Register in [www.dot.tk](http://www.dot.tk)
2. Search and register a free domain name ([projetcompromis.tk](http://projetcompromis.tk) for example).
3. Config the DNS (A and CNAME)

| Domain Name           | Type  | Address               |
|:-------------------   |:---   |:----------------      |
|projetcompromis.tk     |  A    | 192.30.252.153        |
|projetcompromis.tk     |  A    | 192.30.252.154        |
|www.projetcompromis.tk | CNAME | QUXIAOFENG.GITHUB.IO  |

[![DNS Config in dot.tk](/images/dnsconfig.png)](/images/dnsconfig.png)

##### CNAME

>    projetcompromis.tk


Git and Github Config
----------------

1. Register a [Github](https://github.com/) Account
2. Install Git, generate a SSH key, copy the SSH key to your [Github](https://github.com/) account, and set global settings
3. Clone a [jekyll](http://jekyllrb.com/) site (here is the [palmprint repo](https://github.com/quxiaofeng/palmprint) demonstrated in [Palmprint.tk](http://palmprint.tk/) ) in git bash by `git clone git@github.com:quxiaofeng/palmprint.git`
4. Edit all files
5. Remove the old git repo by `rm .git -rf` in the local git folder
6. Initial the new git repo by `git init` in the local git folder
7. Create `gh-pages` as the default branch by `git checkout -b gh-pages` in the local git folder
8. Create a new [Github](https://github.com/) repo in the [Github](https://github.com/) webpage. For example: [`projetcompromis`](https://github.com/quxiaofeng/projetcompromis) (Project Compromise in French)
9. Add the remote address to local git repo by `git remote add origin git@github.com:quxiaofeng/projetcompromis.git` in the local git folder
10. Add all files, commit changes and push to the remote by `git add -A && git commit -sm 'git init the website' && git push -u origin gh-pages`

###### Then we finished the first site like [this](/images/firstsite.png)

[![First Site Screen](/images/firstsite.png)](/images/firstsite.png)

After each modification, just add, commit, and push like this

      git add -A && git commit -sm 'WHAT-YOU-HAVE-DONE' && git push

[Github Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)
----------------

The site is based on [Jekyll](http://jekyllrb.com/)and hosted in [Github](https://github.com/)

Therefore, the pages are in markdown format, and the markdown that the Github using is a little different with general markdown.

HTML5 and CCS
----------------

Design Concept
----------------

+ Responsive design
+ Content and Style should be separated.

Templates and Examples
----------------

+ Different [Jekyll Themes](http://jekyllthemes.org/)
+ Another Starter Guide - [Get Started with Github Pages](http://24ways.org/2013/get-started-with-github-pages/)

TODOs
------------

1. Revising the index page
2. Removing the `contact`, `jobs` and add a `gallery`
3. Updating the `members` - assigned to [`miss-mi`](https://github.com/miss-mi)
4. Editing the CSS style
5. Choosing the color theme
6. Setting up a Virtual machine and the local test environment for the jekyll site.


