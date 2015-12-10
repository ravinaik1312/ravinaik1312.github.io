---
layout: post
title:  "Github Pages and Jekyll"
date:   2015-12-09 17:50:49 -0700
categories: jekyll update
---

# **Pre requisites**
Do you have a github account and not utilizing all it's cool features? You've come to the right place. Today we are going to see in action Github Pages, Github's own platform for hosting static web pages. I will also introduce you to [Jekyll](https://jekyllrb.com/), a simple blog-aware static site generator. This post is in Markdown, so it is kind of a good practice for me to learn Markdown and get used to it's syntax. The only pre requisite for this blog is to have a github account, for rest of the stuff I will provide instructions. 

# **Introduction to Github Pages**
[Github pages](https://pages.github.com/) is used to host static web pages for a repository as it allows one site/domain for every user. It uses the index.html of that repository as an index. You can do a lot of different things with this site, this could be your front page of your repository showcasing all your current work, or it could be a simple site to introduce yourself to the world.  

# **Github Pages in Action**
Quickly I'll get to the point and provide the instruction to get your static website hosted by github up and running. 

1. Sign in to your Github account. 
2. Click on the green 'New Repository' button to create a new repository. This repository will contain the source code for your website. 
3. In the 'Create a new repository' wizard give a valid name to the repository. Don't hush into giving in anyname, this repository name will be the domain name for your website. This page that you are reading off was created in a similar way, so you can give a similar name if you like [ravinaik1312.github.io](http://ravinaik1312.github.io)
4. Make it 'Public' and if you want you can let github to generate the README, gitignore and the license. 
5. Once this is done, create a new file called index.html in your repository and add simple html code 

Here is the code. 

~~~html

<html>
<head>
	<title>Page Title</title>
</head>
<body>
	Hello World
</body>
</html>

~~~

Awesome, commit the changes an allow some time before you hit your repository web site. As per documentation, Github Pages takes about 30 minutes for making the initial domain available. After that, you'll be able to see the changes immediately, meaning any code change will reflect your live web site. Nothing groundbreaking, but you made it, so ...

![Give Yourself a Cookie](http://memegenerator.net/instance/49874629)




