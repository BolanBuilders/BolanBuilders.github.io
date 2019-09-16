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

It should be obvious but this is the small things that can trip up people learning on there own on the web.  It tripped me up and cost me time. Time is valuable, so to anyone who wants to get a website up quickly, this is a critical error. However as a teacher or blogger you can't prevent all critical errors.  Which means you need to have a class room setting to learn these things or you have to trouble shooting skill set.  Not an easy thing for me as a new coder.  Put this rant down to this.  I believe in online universal learning but we have to do it right. Maybe things like Linux User Groups model is better. Maybe we need to combine cheap vr, phone app based and a low res minecraft metting classroom to learn how to create websites with git.
#### git init of project instead of test. Update 03-15-2019
This is what I am trying to do: [Google Searched website](https://kbroman.org/github_tutorial/pages/init.html). Skip down to the "A new reapo from an existing
project."
To quote Karl Broman:
 "Say you’ve got an existing project that you want to start tracking with git.

Go into the directory containing the project.
- Type git init.
- Type git add to add all of the relevant files.
- You’ll probably want to create a .gitignore file right away, to indicate all of the files you don’t want to track. Use git add .gitignore, too.
- Type git commit."
Point 3 I did when I uploaded via the website with the website interface.
Point 1 I did before googling, after I backed up my website files because after
mytest tutorial above it seemed the right thing to do.
Point 2 seemed not enough information, because I have a lot of files. So further
google fu brought up theses websites.
 1. [Stack Overflow](https://stackoverflow.com/questions/19576116/how-to-add-multiple-files-to-git-at-the-same-time). In that I found a comment useful:
 "If you want to add all files you can use ` git add -a ` .But if you want to add multiple selected files. you can use ` git add -i ' . please refer this git-scm.com/book/en/v2/Git-Tools-Interactive-Staging . this will help you . – Kapila Ranasinghe Sep 17 '16 at 6:27". I followed that link to the 2nd link.
 2. [Gits online book](https://git-scm.com/book/en/v2/Git-Tools-Interactive-Staging)

 update a full log will be in a seperate post but It's quitin time and I will have
 to research this error later.   
 ```
 To https://github.com/BolanBuilders/BolanBuilders.github.io
  ! [rejected]        master -> master (fetch first)
 error: failed to push some refs to 'https://github.com/BolanBuilders/BolanBuilders.github.io'
 hint: Updates were rejected because the remote contains work that you do
 hint: not have locally. This is usually caused by another repository pushing
 hint: to the same ref. You may want to first integrate the remote changes
 hint: (e.g., 'git pull ...') before pushing again.
 hint: See the 'Note about fast-forwards' in 'git push --help' for details.
 johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog/BolanBuilder.github.io$ ```

 I didn't make any website edits, other then making folders and an empty ph.txt via
 website.  Maybe that is it.




### Think about what tags, topics, or categories of content you want.

I want a vanity page about me. Another page communicates my Projects or Portfolio. This website contains a reactions or current event page.  A Documentation page, which might be the projects page.  A Sticky Page for Important articles, think a web forum stick post. I also going to include a "FUD" page, A truthful page with points about evil, hellfire,etc. An Index page with navigation to tie all this together.  How about an old fashioned links or bookmark page with a tweet length max explanation on why I found that interesting.
Helpful site  if using Jekyll [webjeda](https://blog.webjeda.com/jekyll-categories) and from youtube university [GiraffeAcademy](https://www.youtube.com/c/GiraffeAcademy).
Update 03-27-2019:  Reading through the Jekyll Documentation some things have changed minorly since webjeda posted.
They have links for tutorials on the website.  Look through them. [Cloud Cannon](https://learn.cloudcannon.com/) wants you to use their service.
They look like they have a well thought out tutorial for the static site generator, Jekyll.

Update: March 9th 2019: So far I  have created these base pages and  a skeleton of links for them in the navigation.
Update: updated links.
I had put in liquid permalinks in my files:

```
---
permalink: /index/
---
```

to:

```
---
permalink: /index.md
---
```

to:

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
to:

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
You can always get pictures, effects, videos, gifs,etc later. I cringe at the thought
of gifs but Lifehacker does that tastefully.

### Create css

Find Background
set links style
Set Font data
Update 03272019: So I neglected to do a post on my css. I just banged it out.
[Interneting is Hard ](https://internetingishard.com/) is invaluable.
 Still have a lot to do as in my [Head Trama Website]() post.

 Unfortunately I don't know how to link to my own posts yet so if the link doesn't
work you will have to find it on your own. It is not yet posted so I don't have
a web browser link yet. I need to copy it out of my web browser and paste into the
link creating a hard link. That will break if I move things around.
Relative links would be really nice to know right now.

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
