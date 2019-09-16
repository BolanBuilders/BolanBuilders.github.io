---
layout: post
title: Broke Jekyll local serve
categories: documentation
published: true
---



### Error got this bash output

I don't even know what I did.
I changed my _config.yml by adding my base url and my github website url.
But that doesn't seem related.
For the fist part I have a ``` _layouts/post.html ``` it has always worked before.

~/Documents/BolanBuilderBlog/BolanBuilders.github.io$ bundle exec jekyll serve
Configuration file: none
            Source: /home/johnbolan/Documents/BolanBuilderBlog/BolanBuilders.github.io
       Destination: /home/johnbolan/Documents/BolanBuilderBlog/BolanBuilders.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-06-HowToCreateAWebsite.md does not exist.
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-09-2ndPostRockShow.md does not exist.
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-09-TrumpIsDumb.md does not exist.
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-11-welcome-to-jekyll.markdown does not exist.
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-12-logGitInstall.md does not exist.
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-15-BashLogGitWebsiteFistCommit.md does not exist.
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-15-IHaveFeelings.md does not exist.
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-18-StylesBrainstorm.md does not exist.
     Build Warning: Layout 'post' requested in BolanBuilders.github.io/_posts/2019-03-20-NukeItFromTerminal.md does not exist.
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
   GitHub Metadata: Error processing value 'title':
  Liquid Exception: No repo name found. Specify using PAGES_REPO_NWO environment variables, 'repository' in your configuration, or set up an 'origin' git remote pointing to your github.com repository. in /_layouts/default.html
             ERROR: YOUR SITE COULD NOT BE BUILT:
                    ------------------------------------
                    No repo name found. Specify using PAGES_REPO_NWO environment variables, 'repository' in your configuration, or set up an 'origin' git remote pointing to your github.com repository.
johnbolan@JohnBolan-Gazelle-Professional:~/Documents/BolanBuilderBlog/BolanBuilders.github.io$
