---
layout: post
title: Git First Commit
categories: documentation
published: true
---

## First Commit to BolanBuilders.github.io Bash Log
**johnbolan@JohnBolan-Gazelle-Professional:~$** cd /Home/Documents/BolanBuilderBlog
bash: cd: /Home/Documents/BolanBuilderBlog: No such file or directory
**johnbolan@JohnBolan-Gazelle-Professional:~$** cd /home/johnbolan/Documents/BolanBuildersBlog
bash: cd: /home/johnbolan/Documents/BolanBuildersBlog: No such file or directory
**johnbolan@JohnBolan-Gazelle-Professional:~$** cd /home/johnbolan/Documents/BolanBuilderBlog/
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** ls
20190315websitebackup.tar.gz  BolanBuilder.github.io
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** ls -l
total 196
-rw-rw-r--  1 johnbolan johnbolan 195094 Mar 15 19:01 20190315websitebackup.tar.gz
drwxrwxr-x 10 johnbolan johnbolan   4096 Mar 13 21:09 BolanBuilder.github.io
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** git init BolanBuilder.github.io
Reinitialized existing Git repository in /home/johnbolan/Documents/BolanBuilderBlog/BolanBuilder.github.io/.git/
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** git add -i
fatal: not a git repository (or any of the parent directories): .git
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** cd ~/BolanBuilder.github.io
bash: cd: /home/johnbolan/BolanBuilder.github.io: No such file or directory
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** cd ~/BolanBuilder.github.io
bash: cd: /home/johnbolan/BolanBuilder.github.io: No such file or directory
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** ls
20190315websitebackup.tar.gz  BolanBuilder.github.io
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** cd /BolanBuilder.github.io
bash: cd: /BolanBuilder.github.io: No such file or directory
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** pwd
/home/johnbolan/Documents/BolanBuilderBlog
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** cd /home/johnbloan/Documents/BolanBuilderBlog/BolanBuilder.github.io
bash: cd: /home/johnbloan/Documents/BolanBuilderBlog/BolanBuilder.github.io: No such file or directory
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** /home/johnbolan/Documents/BolanBuilderBlog/BolanBuilder.github.io/
bash: /home/johnbolan/Documents/BolanBuilderBlog/BolanBuilder.github.io/: Is a directory
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** ls
20190315websitebackup.tar.gz  BolanBuilder.github.io
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog$** cd /home/johnbolan/Documents/BolanBuilderBlog/BolanBuilder.github.io/
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog/BolanBuilder.github.io$** ls
 404.html           Gemfile        _posts                                              '_posts\2019-03-12-logGitInstall.html'
 about.md           Gemfile.lock  '_posts\2019-02-03-AboutMeJohnBolan.html'             Pure.md
 _config.yml        _includes     '_posts\2019-03--06-HowToCreateAWebsite.html'        'Read me.md'
 _data              index.md      '_posts\2019-03-09-2ndPostRockShow.html'              Religion.md
 Documentation.md   _layouts      '_posts\2019-03-09-TrumpIsDumb.html'                  _site
 _drafts            Links.md      '_posts\2019-03-11-welcome-to-jekyll.markdown.html'   StickyPages.md
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog/BolanBuilder.github.io$** git add -i
           staged     unstaged path
  1:        +3/-0      nothing .gitignore
  2:       +25/-0      nothing 404.html
  3:        +9/-0      nothing Documentation.md
  4:       +29/-0      nothing Gemfile
  5:       +74/-0      nothing Gemfile.lock
  6:       +10/-0      nothing Links.md
  7:        +4/-0      nothing Pure.md
  8:        +4/-0      nothing Read me.md
  9:       +15/-0      nothing Religion.md
 10:        +9/-0      nothing StickyPages.md
 11:       +43/-0      nothing _config.yml
 12:        +6/-0      nothing _includes/head.html
 13:       +14/-0        +7/-7 _includes/navigation.html
 14:       +26/-0      nothing _layouts/default.html
 15:       +28/-0        +5/-2 _layouts/post.html
 16:       +23/-0      nothing _posts/2019-02-03-AboutMeJohnBolan.md
 17:      +141/-0      nothing _posts/2019-03--06-HowToCreateAWebsite.md
 18:        +9/-0      nothing _posts/2019-03-09-2ndPostRockShow.md
 19:       +61/-0      nothing _posts/2019-03-09-TrumpIsDumb.md
 20:       +25/-0      nothing _posts/2019-03-11-welcome-to-jekyll.markdown
 21:      +136/-0      nothing _posts/2019-03-12-logGitInstall.md
 22:       +47/-0      nothing _posts\2019-02-03-AboutMeJohnBolan.html
 23:      +121/-0      nothing _posts\2019-03--06-HowToCreateAWebsite.html
 24:       +35/-0      nothing _posts\2019-03-09-2ndPostRockShow.html
 25:       +68/-0      nothing _posts\2019-03-09-TrumpIsDumb.html
 26:       +44/-0      nothing _posts\2019-03-11-welcome-to-jekyll.markdown.html
 27:      +159/-0      nothing _posts\2019-03-12-logGitInstall.html
 28:       +18/-0      nothing about.md
 29:       +19/-0        +1/-1 index.md

*** Commands ***
  1: status       2: update       3: revert       4: add untracked
  5: patch        6: diff         7: quit         8: help
What now> 4
  1: _posts/2019-03-15-IHaveFeelings
Add untracked>> 1
* 1: _posts/2019-03-15-IHaveFeelings
Add untracked>> 2
* 1: _posts/2019-03-15-IHaveFeelings
Add untracked>> 3
* 1: _posts/2019-03-15-IHaveFeelings
Add untracked>> 6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,29
* 1: _posts/2019-03-15-IHaveFeelings
Add untracked>>
added 1 path

*** Commands ***
  1: status       2: update       3: revert       4: add untracked
  5: patch        6: diff         7: quit         8: help
What now> q
Bye.
****johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog/BolanBuilder.github.io$**** git commit -m "website text updates, new posts, editing"
[master (root-commit) f543848] website text updates, new posts, editing
 30 files changed, 1259 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 404.html
 create mode 100644 Documentation.md
 create mode 100644 Gemfile
 create mode 100644 Gemfile.lock
 create mode 100644 Links.md
 create mode 100644 Pure.md
 create mode 100644 Read me.md
 create mode 100644 Religion.md
 create mode 100644 StickyPages.md
 create mode 100644 _config.yml
 create mode 100644 _includes/head.html
 create mode 100644 _includes/navigation.html
 create mode 100644 _layouts/default.html
 create mode 100644 _layouts/post.html
 create mode 100644 _posts/2019-02-03-AboutMeJohnBolan.md
 create mode 100644 _posts/2019-03--06-HowToCreateAWebsite.md
 create mode 100644 _posts/2019-03-09-2ndPostRockShow.md
 create mode 100644 _posts/2019-03-09-TrumpIsDumb.md
 create mode 100644 _posts/2019-03-11-welcome-to-jekyll.markdown
 create mode 100644 _posts/2019-03-12-logGitInstall.md
 create mode 100644 _posts/2019-03-15-IHaveFeelings
 create mode 100644 "_posts\\2019-02-03-AboutMeJohnBolan.html"
 create mode 100644 "_posts\\2019-03--06-HowToCreateAWebsite.html"
 create mode 100644 "_posts\\2019-03-09-2ndPostRockShow.html"
 create mode 100644 "_posts\\2019-03-09-TrumpIsDumb.html"
 create mode 100644 "_posts\\2019-03-11-welcome-to-jekyll.markdown.html"
 create mode 100644 "_posts\\2019-03-12-logGitInstall.html"
 create mode 100644 about.md
 create mode 100644 index.md
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog/BolanBuilder.github.io$** git remote add origin https://github.com/BolanBuilders/BolanBuilders.github.io
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog/BolanBuilder.github.io$** git push origin master
Username for 'https://github.com': BolanBuilders
Password for 'https://BolanBuilders@github.com':
To https://github.com/BolanBuilders/BolanBuilders.github.io
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/BolanBuilders/BolanBuilders.github.io'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
**johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog/BolanBuilder.github.io$**
