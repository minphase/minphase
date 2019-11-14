---
permalink: /submission/submission/
title: "Make a submission"
excerpt: "How to quickly install and setup Minimal Mistakes for use with GitHub Pages."
last_modified_at: 2019-11-01T08:06:00-05:00
toc: true
---

This page will show you how to make a submission to MinPhase.com. 

## What we're looking for in a post
You can make a post about a solution of a problem you want to share or a link to an interesting video, article or similar. Our only requirements is that the technical details should be the focus. 


## How to write a post
The site is generated with jekyll and the posts are written in markdown. If you are unfamiliar wih markdown you can have a look at [markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). There are a lot of good sources available online on how to use markdown. To preview what you have written you can use an editor like Visual Studio Code or Atom where you can download markdown preview packages. They wont show exactly how the post will look on this website since that is dependent on the Jekyll configuration. This website is using the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme. 


To get started you can have a look at this [template page](/article/template-page/). It shows how things look on the website and the code that generated the post is available at the bottom of the page.


### Filename 
The filename should contain the date you wrote it. E.g.

```
2019-11-14-your-filename.md
```

### Front matter
Every post needs front matter, it sets some variables for the webpage. The following are the standard ones you always should use and then below are some optional ones that you can have if you want. A standard page will look something like the [page template](/article/template-page/).

```markdown
---
title:  "Your title"
excerpt: "Excerpt text that will be shown as preview for the post."
author: Your Name
header:
  teaser: "/assets/images/your_teaser_image.png"
categories: 
  - article / link
tags:
  - Your Name
  - Tag
  - describing 
  - your post
---
```

Title sets the title on the page. The excerpt will be the preview text under the link to the post, see the [frontpage](/) for an example. The author field specifies the author that will be on the side of the page. In the header you can set a teaser image which will be shown in some places, see the [authors page](/authors/) for an example. Category specifies if your post is an article or if you're sharing an interesting link. So if you're writing an article you should use **article** and if you're sharing an link you should use **link**. Tags are searchable so you should put your name there and also other relevant tags to your topic.

#### Disabling your author profile
Maybe you want to share a link but not have your author profile on the side or any other reason.
You can disable your author profile by adding the following to your front matter. 
```
author_profile: false
```


#### Table of contents
You can add a table of contents on the right side, like the one this post has. To do this you need set table of contents to true in the front matter by adding **toc: true**, it is set to false by default.

```
toc: true
```

#### Header image 
You can add a header image to the top of your page. It is done by adding the following to your front matter.
There is also a [template page](/article/template-header-image/) that shows how to do this and how it can look. 

```markdown
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header_image.jpg
```


##### Header video
If you want to have a video as a header instead you can add the following to you front matter. There is also a [template page](/article/template-header-video/) for this which will give you more information on how to do this.

```markdown
header:
  video:
    id: yYAw79386WI
    provider: youtube
```


### Making an author profile
On the left side of your post there will be a profile of you. You can choose what you want to be shown there. Below are a list of things that can be added, where some things are optional. This information can be specified in a text file or a mail, and the image should be sent in as a file or a link to it. 

* Image: profile image
* Name: your name
* Bio: A short text that will be shown under you name.
* Email: Your email address. (optional)
* Website: link to your website. (optional)
* GitHub: Link to your github. (optional)
* LinkedIn: Link to your profile. (optional)
* Facebook: Link to your profile. (optional)
* Twitter: Link to your profile. (optional)
* Something else: Link to it. (optional)


## How to submit a post
We haven't decided yet on a way of submitting posts, but if you get in contact with us we could work something out.

### Submission checklist
Here is a small checklist of files that are needed to submit a post

* Your post written in markdown
* The pictures you have included in the post

If you haven't submitted something in the past and don't have a profile on this page you also need to submit:
* Author profile in the way that is specified above.
* Profile picture

