---
layout: post
title: How to Create a Website
categories: documentation
published: true
---

# How to Create a Website
## Documentation of My Process
---

### Choose Host

Signed up for Git Hub Account.  Git Hub has Git Hub Pages. Git Hub has some competitors because Microsoft bought them. Choose wisely.

Create a repository for your project web page.
[Here](jmcglone.com/guides/github-pages) is a website with website editing of a page on GitHub and some Jekyll instructions.  

Update:  I am going to try and install git.
I am following these instructions and they seem to be working well.
[Instrutions HotJar](https://www.howtoforge.com/tutorial/install-git-and-github-on-ubuntu/)

To install github I actually used a different website which I no longer have.
The only acctions I took from that is to install a ppa and the git program.  Here is a [log](2019-03-12-logGitInstall) for you to see.

### git tuturoial problem

Also in the step were you add files to local repository via the ``` git add ``` command it doesn't mention that you have to be in the same folder of mytest for it to work.  
#### rant

It should be obvious but this is the small things that can trip up people learning on there own on the web.  It triped me up and cost me time. Time is vaulable, so anyone who wants to get a website up quickly this is a critical error. However as a teacher or bloger you cant prevent all critlical errors.  Which means you need to have a class room setting to learn these things or you have to trouble shooting skill set.  Not an easy thing for me as a new coder.  Put this rant down to this.  I beleive in online universal learning but we have to do it right. Maybe things like Linux User Groups model is better. Maybe we need to combine cheap vr, phone app based and a low res minecraft metting classroom to learn how to create websites with git.
### Think about what tags, topics, or catagories of content you want.

I want a vanity page about me. Another page communicates my Projects or Portfolio. This website contains a reactions or current event page.  A Documentation page, which might be the projects page.  A Sticky Page for Important articles, think a web forum stick post. I also going to include a "FUD" page, A truthful page with points about evil, hellfire,etc. An Index page with navigation to tie all this together.  How about an old fashioned links or bookmark page with a tweet length max explanation on why I found that interesting.
Helpful site  if using Jekyll [webjeda](https://blog.webjeda.com/jekyll-categories).

Update: March 9th 2019: So far I  have created these base pages and  a skeliton of links for them in the navigation.
Update: updated links.
I had put in liquid permalinks in my files.

```
---
permalink: /index/
---
```

to

```
---
permalink: /index.md
---
```

to

```
---
permalink: /index
---

```
That finally worked better on my local host website server that I was running
 as for the header navigation here is my code.
 ```
 <h3><li>
 <<a href="index.md">Home</a>
 <a href="StickyPages.md">Sticky Page</a>
 <a href="Documentation.md">Documentation Posts</a>
 <a href="about">About Site.md</a>
 <a href="Religion.md">Religion</a>
 <a href="Links.md">Links and Bookmarks</a>
 <a href="Pure.md">Pure Html Lundukedom Style</a>
 </li></h3>

 ```
to

```
<h3><li>
<<a href="index">Home</a>
<a href="StickyPages">Sticky Page</a>
<a href="Documentation">Documentation Posts</a>
<a href="about">About Site</a>
<a href="Religion">Religion</a>
<a href="Links">Links and Bookmarks</a>
<a href="Pure">Pure Html Lundukedom Style</a>
</li></h3>

```
Again because the previous code didn't work.  The file ending is not needed. Live and learn.
Caveat, I am running Jekyll so .md would be .html files if you were hand coding the site.

[Home](index)
- [Sticky Page](StickyPages)
- [Documentation Posts](Documentation)
- [About Me & Contact](about)
- [Religion](Religion)
- [Links and Bookmarks](Links)
- [Pure html](Pure)

### Create Text Content
You can always get pictures, effects, videos, gifs,etc later. I cringe at the thought of gifs but life hacker does that tastefully.

### Create css

Find Background
set links style
Set Font data

### Become familiar with GitHub GUI

Explore, poke, and watch YouTube videos.  See

### Upload Files to GitHub
This seems to be harder then I thought.  I tried to drag my whole local blog folder and upload but it errored out.
going to try to set up git via CLI.  

### Hyperspace Files
Do I want a premade website?  http://html5up.net  So far no, I do want to be familiar with css.

###  Jekyll Premade themes and color page
[Jekyll Themes:]( http://jekyll-themes.com) http://jekyll-themes.com

[Colors:]( www.flatuicolorpicker.com) www.flatuicolorpicker.com

### FormSpree contact page
??? maybe

### Sitemap

https://blog.webjeda.com/jekyll-sitemap/

### Editing Jekyell blog

https://blog.webjeda.com/edit-posts-jekyll/

### Subscribe Chimp

??? maybe
https://blog.webjeda.com/jekyll-subscribe-form/
