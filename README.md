# Contributing to [The PS2 Homebrew Wiki](https://ps2wiki.github.io)!
Hello there! Welcome to PS2Wiki! If you are here in this repository then you have atleast had a thought of contributing to the Wiki, be it in a small way or a big idea. This README will walk you through all the basics you need to know to work with PS2Wiki's content files, so even if you have never worked with html or markdown, you'll know where and how to start.

> [!IMPORTANT]\
> This page is incomplete and is in progress of being updated, check back in a few days to see if anything has changed. Thanks!

## What can I contribute?
Anything. Be it a post idea, feature enhancement request, tutorial or guide, or full on code. Below sections will explore how you can help in each way.


  ### Table of Contents
  - [How do Posts work?](#How-do-Posts-work?)
    - [Structure in the Repository](#Structure-in-the-Repository)
    - [Naming of the Post file](#Naming-of-the-Post-file)
    - [Contents of the Post file](#Contents-of-the-Post-file)
    - [Publishing your Post](#Publishing-your-Post)
     

## How do Posts work?
### Structure in the repository
Every post on PS2Wiki is contained within the ```_posts``` folder, and while anything you put there with the ```.md``` extension will appear on the site. However, due to the size and scope of the wiki just having files in the root of the directory will become cumbersome and difficult to manage. In order to mitigate this, there are "Topic" folders within the main directory, within those there are individual post folders as well (have same name as the .md file), and within this folder is your main ```post.md``` and as many files or folder as your document requires for a better User Experience. This includes files like any photos or videos (refrain from adding in very large files though) or anything else which you might need to call upon.  
</br>

### Naming of the Post file
Each post file **has to follow** the format: ```yyyy-mm-dd-post-name-can-be-whatever.md``` in the name in order top be parsed into the site. This also has to be how you name your folder (except for .md in the name).  
Following the convention, your file should be in the following path: ```_posts/Topic/yyyy-mm-dd-post-name-can-be-whatever/yyyy-mm-dd-post-name-can-be-whatever.md```.  
</br>

### Contents of the Post file
While you can put anything you want within the post itself, make sure that the first few lines are **always**:
```
---
layout: post
title: <your title here>
subtitle: <your subtitle here>
author: <your name>
wiptag: <Not Complete/Completed>
categories: <topic of the post, eg: OPL, wLaunchELF; for existing topics, visit: https://ps2wiki.github.io/categories.html>
banner: 
  image: <link to banner image, can be internal link or external, it's upto you>
  opacity: 0.5 
image: <same as above, this will appear in shared links or on the 'Latest Posts' section in 'Home'>
tags: <anything relevant, eg: SAS Beginner FAQ ; separated by space>
---

<your content>
```
> [!Note]\
> Replace text in `<>` with your own options.  
</br>

### Publishing your Post
After you have your markdown ready, you can either clone the repo (clone the 'main' branch, not 'upstream') and make a [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) or raise an issue [here](https://github.com/ps2wiki/ps2wiki.github.io/issues/new?assignees=koraxial&labels=documentation%2Cpost-idea&projects=&template=post-ideas.yml&title=%5BPost+Idea%5D%3A+) and fill the issue form and attach the files there (use .zip or .7z so structure is maintained).  
Once your files are reviewed, they will be added to the main repo in a few days time. 
> [!Note]\
> Incase your changes aren't merged within a week, you can open an issue (if you made a PR) or if you already opened one, drop in a message again.  
</br>

