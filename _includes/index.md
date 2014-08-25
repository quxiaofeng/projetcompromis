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


Git and Github
----------------

### Git Install and Config

#### 1. Download Git from [Official Website](http://git-scm.com/download/win) or [download manually](https://github.com/msysgit/msysgit/releases/download/Git-1.9.4-preview20140815/Git-1.9.4-preview20140815.exe)

![](/images/download-git.png)

#### 2. Install Git with recommended settings

![](/images/git-install-path-options.png)

This option is normally safe and powerful enough for git users.

![](/images/git-install-line-ending-options.png)

This option preserves the original line endings and commits platform independent codes.

#### 3. Generate SSH key using **Git Bash**

Check local ssh keys

    $ cd ~/. ssh
    $ ls

Backup local ssh keys if there are already some

    $ mkdir key_backup
    $ cp id_rsa* key_backup
    $ rm id_rsa*

Finally generate a new key using your email address

    $ ssh-keygen -t rsa -C "your@email.address"

#### 4. Copy the public key and paste it to your github account

    $ vim ~/.ssh/id_rsa.pub

In windows, *Mark* and copy like this. (Exit `vim` by pressing `ESC` - `:q` - Enter)

![](/images/git-install-mark-in-windows.jpg)

And then *Paste* the public ssh key to your github account like this.

Open `Github.com` - `Settings` - `SSH keys` - `Add SSH key`, name a title (usually the computer nickname) and paste the public SSH key.

![](/images/github-add-ssh-key-menu.png)

#### 5. Set Git global settings in **Git Bash**

    $ git config --global user.name "Your Name in English"
    $ git config --global user.email "your@email.address"
    $ git config --global push.default matching

Check the global settings by `git config --list`

#### 6. Test the Github connection

    $ ssh –T git@github.com

#### Further information of Git can be found with

    $ git --help
    $ git status --help
    $ git add --help
    $ git commit --help
    $ git push --help
    $ git remote --help

### Github Config

1. Register a [Github](https://github.com/) Account

2. Clone a [jekyll](http://jekyllrb.com/) site (here is the [palmprint repo](https://github.com/quxiaofeng/palmprint) demonstrated in [Palmprint.tk](http://palmprint.tk/) ) in git bash by `git clone git@github.com:quxiaofeng/palmprint.git`

3. Edit all files

4. Remove the old git repo by `rm .git -rf` in the local git folder

5. Initial the new git repo by `git init` in the local git folder

6. Create `gh-pages` as the default branch by `git checkout -b gh-pages` in the local git folder. (**gh-pages** branch is the *default* github pages branch.)

7. Create a new [Github](https://github.com/) repo in the [Github](https://github.com/) webpage. For example: [`projetcompromis`](https://github.com/quxiaofeng/projetcompromis) (Project Compromise in French)

8. Add the remote address to local git repo by `git remote add origin git@github.com:quxiaofeng/projetcompromis.git` in the local git folder

9. Add all files, commit changes and push to the remote by `git add -A && git commit -sm 'Init the website' && git push -u origin gh-pages`

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


