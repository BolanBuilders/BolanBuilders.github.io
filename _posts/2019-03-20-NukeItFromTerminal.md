---
layout: post
title: Nuke It From Orbit (Terminal)
categories: documentation
published: true
---


## Nuke it from the terminal.
So Jekyll stoped serveing. My local git never did talk to by github account.
Out or frustration I

``` BlahBhaH$ rm -R /home/Documents/Blog/BolanBuilders.github.io ```

I am paraphraseing but it felt good.  So I decided to try everything over again.
Watch for my 3rd incoming terminal log post. I will name it TerminalVelocity.md.
HTML needs a pun tag.  RFC submission anyone?
Anyway links for tutorial to get back up and running are to follow.

### Reading instructions

  You have to look at their code boxs
and modify.  For example:

```
$ bundle exec jekyll _3.3.0_ new NEW-JEKYLL-SITE-REPOSITORY-NAME
> New jekyll site installed in /Users/octocat/NEW-JEKYLL-SITE-REPOSITORY-NAME.

```

In that your not entering the $ and you are going to replace the all caps with
your, in this particular example, repository name.  Mine is of course
BolanBuilders.github.io. This is only included because I remember throwing away
linux for 6 years because I was in the termial in Xandros OS. The windows like
linux of the day, because all the websites instructions included that dang dollar
sign. and the > symbol is just short hand for 'it will return something like this'.

### Links to tutorial
[Github 1](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll)
[Github 2](https://help.github.com/en/articles/syncing-a-fork)

### Results
It didn't work.  I still haven't figured out the git stuff. but Jeykll is at least
serving a local website.
My Css is working in the top lvl website but all the posts don't.  I don't have the
foggest why. They all have the exact same head because I seperated it out in _includes
and put the head with includes in my default and post html template files. As soon as
you go past the root lvl folder in the navigation bar we lose css.  Another Day ,
Another mystery.  A theme would be a whole lot eaiser but I wouldn't know how links work.
See you later.
