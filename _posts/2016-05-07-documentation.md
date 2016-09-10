---
layout: post
title: Documentation
img: image-5.png
---


# Installation: 
Fork the ``master`` branch and delete ``gh-pages`` branch in it. This is important because ``gh-pages`` branch is used here only to host the blog. You should be using the master branch as the source and create a fresh ``gh-pages`` branch.

Watch my video on instlallation
<iframe width="100%" height="360" src="https://www.youtube.com/embed/T2nx6tj-ZH4?rel=0" frameborder="0" allowfullscreen></iframe>

## How to delete old **gh-pages** branch?
After forking the repository, click on **branches**.

![delete gh-pages branch](http://blog.webjeda.com/images/delete-github-branch.png)

Delete ``gh-pages`` branch.
![delete gh-pages branch](http://blog.webjeda.com/images/delete-github-branch-2.png)

You have to create a new ``gh-pages`` branch using the master branch. Go back to the forked repository and create ``gh-pages`` branch.

![create gh-pages branch](http://blog.webjeda.com/images/create-gh-pages-branch.JPG)

Now, go to settings and check the **Github Pages** section. You should see a URL where the blog is hosted.

This process will host the theme as a **Project Page**. You can also download the files for local development. 

Default theme will look like this

![webjeda gatok jekyll theme]({{site.baseurl}}/images/webjeda-gatok-jekyll-theme-screenshot-1.png)

Hover on the left side for a 3d sidebar!

![webjeda gatok jekyll theme sidebar]({{site.baseurl}}/images/webjeda-gatok-jekyll-theme-screenshot.jpg)


This theme is responsive.

![webjeda gatok responsive jekyll theme]({{site.baseurl}}/images/webjeda-gatok-jekyll-theme-screenshot-2.png)
{: .text-center}


# Development
Make changes to the **master** branch and create a pull request. Do not use **gh-pages** branch as it is used to host the theme.


# License
MIT License

# Change Log

### Version 1.0
* Fixed flashing menubar. 
* SEO optimization. Disqus is installed by default. 
* Compression is removed. Add ```layout: compress``` to the front matter of default layout to compress html.

### Version 0.8
* Initial release with 3D menu and minimal layout.
