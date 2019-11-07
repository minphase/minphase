---
title: "Front matter"
author: Dennis Edblom
---
Front matter is used in Jekyll websites to set variables for a page such as title, layout, author and so on. For more information on front matter you can have a look at the [Jekyll front matter documentation](https://jekyllrb.com/docs/front-matter/).


Front matter variables can vary depending on your Jekyll application. If you use a pre-made theme then  the author of the theme can have made their own variables that you need to set. Here i will just talk about what the front matter on this site does and how you can use it to customize your post.

## How to use front matter
The front matter must must be the first thing in the file and is written in YAML format between triple-dashed lines. This page has for instance the following front matter:

```Markdown
---
title: "Front matter"
author: Dennis Edblom
---
```

## Examples of front matter 

The front matter variables in the Minimal Mistakes Jekyll theme that are useful for posts are:

* title
* layout
* 

header:
  teaser: path-to-teaser-image.jpg


search: false

header:
  image: /assets/images/image-filename.jpg

header:
  image: /assets/images/unsplash-image-1.jpg
  image_description: "A description of the image"


header:
  image: /assets/images/unsplash-image-1.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
