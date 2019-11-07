---
title:  "Writing with markdown."
author: Dennis Edblom
categories: 
  - submission
tags:
  - dennis-edblom
  - markdown
last_modified_at: 2019-11-06T08:06:00-05:00
toc: true
---

This post will help you get started with writing in markdown. Markdown has different parsers and this site uses [kramdown](https://kramdown.gettalong.org/index.html). The different parsers are mostly the same. Markdown is a good tool for formatting text easily and can be used for creating static websites with Jekyll or when writing a readme for your GitHub repository. This page is available at TODO: link to source code [github.com/minphase/minphase/_posts/writngkjak](github.com/minphase/minphase/_posts/writngkjak)

## Standard things

### How to make headers
It's easy to make headers with markdown. Headers are made with the # symbol and the number of # decides what level the header is. Below follows examples for headers from level 1 to 4. How the headers look is dependant on the application and the choices made there, for instance on this website the look is decided by the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme.

# Level 1
```
# Level 1
```

## Level 2
```
## Level 2
```

### Level 3
```
### Level 3
```

#### level 4
```
#### Level 4
```


### How to make code blocks
Markdown has code blocks which is very good for sharing snippets of code. 

This is a code block without highlighting.


<pre lang="no-highlight">
<code>
```
# This is a code block with no highlighting.
for x in range(6):
  print(x)
else:
  print("Done!") 
```
</code>
</pre>

```
# This is a code block with no highlighting.
for x in range(6):
  print(x)
else:
  print("Done!") 
```

---
You can also choose syntax highlighting.

<pre lang="no-highlight">
<code>
```python
# This is a code block with python highlighting
for x in range(6):
  print(x)
else:
  print("Done!") 
```
</code>
</pre>

```python
# This is a code block with python highlighting
for x in range(6):
  print(x)
else:
  print("Done!") 
```

### how to add links.

To add a normal link use the following.
```markdown
[text that will be shown](link)
```

If you don't want the link to redirect you but you instead want it to open in a new tab then use.

```markdown
[text that will be shown](link){:target="_blank"}
```

### how to make lists

### math







## Stuff that is jekyll theme specific

### frontmatter
TODO: link to different templates where people can see what does what.

### images
### youtube



## tips and tricks

### How to see how it will look on the website
You can use an editor like vscode or atom to get a preview of how the markdown file will look but this doesnt show how it will look on the website. If you want to see exactly how your post will look on the website you will have download the github repository and host the site locally on your computer. A guide on how to setup local hosting of jekyll sites can be found here. TODO: make guide on how to locally host websites with jekyll.

This is a bit harder