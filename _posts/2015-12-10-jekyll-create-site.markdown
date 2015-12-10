---
layout: post
title:  "Static site with Jekyll"
date:   2015-12-09 17:50:49 -0700
categories: jekyll update
---

# **Flashback**
In my last blog post, we saw how to host a simple web site on Github pages. In this one, we will go a step further and use Jekyll to automatically create us a static web site and use that to host it on Github Pages. 

# **Jekyll in Action**
The first thing you need to do is to install Jekyll on your machine. It is basically a ruby package, so you will need to have 'gem' first. 

~~~bash
gem install jekyll
~~~

Once you have installed it is as easy as 123... to create an awesome static blog-aware website and then customize it as you want. 

Execute the following instructions on your terminal. 

~~~bash
jekyll new my-new-website
cd my-new-website
jekyll serve
~~~

Head to your browser at http://localhost:4000 to see what jekyll created for you. 

# **Jekyll and Github Pages**
Now that you have a website, you can use Github pages to host it. Copy over all the folders created by Jekyll to your Github Repository that you created in the previous post. Once, you commit these changes to your repository, it gets automatically reflected and Githb pages will ne hosting the site that you have created using Jekyll. 