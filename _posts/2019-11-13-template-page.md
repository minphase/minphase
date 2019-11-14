---
title: "Template page"
author: Dennis Edblom
categories: 
  - article
tags:
  - Dennis Edblom
  - template
last_modified_at: 2019-11-07T08:06:00-05:00
header:
  teaser: "/assets/images/your-teaser-image.png"
---

This page is just a template to help you get started with writing. **The code can be found at the [bottom of this page](/article/template-page/#code-that-generated-this-site)**. The file is also available on [Github](https://github.com/minphase/minphase/blob/master/_posts/2019-11-13-template-page.md). 

# This is a level 1 header
It's the same size as the page title.

## This is a level 2 header
Some text.

### This is a level 3 header
More text.

#### Level 4 header
Even more text.

### List 
* list item 1
  * list item 1.1
    * list item 1.1.1
  * list item 1.2
* list item 2

### Table

| item 1 | item 2 | item 3 | item 4 |
|--------|--------|--------|--------|
| 10     |  20    | 30     |  40    |
| 20     |  40    | 10     |  20    |

### Code block
```python
reduce(lambda x, y: x * y, range(1, n+1))
```

### Math

$$ \sum_{k=1}^\infty \frac{1}{k^2} = \frac{\pi^2}{6} $$

$$4+2 = 6$$

### Image

<figure>
  <img src="{{ '/assets/images/your-teaser-image.png' | relative_url }}" alt="indented paragraph example">
  <figcaption>Example of including an image.</figcaption>
</figure>

### Video

{% include video id="6YLMWU-5H9o" provider="youtube" %}

## Code that generated this site


~~~markdown
---
title: "Template page"
author: Dennis Edblom
categories: 
  - article
tags:
  - Dennis Edblom
  - template
last_modified_at: 2019-11-07T08:06:00-05:00
header:
  teaser: "/assets/images/your-teaser-image.png"
---

This page is just a template to help you get started with writing. **The code can be found at the [bottom of this page](/article/template-page/#code-that-generated-this-site)**. The file is also available on [Github](https://github.com/minphase/minphase/blob/master/_posts/2019-11-13-template-page.md). 

# This is a level 1 header
It's the same size as the page title.

## This is a level 2 header
Some text.

### This is a level 3 header
More text.

#### Level 4 header
Even more text.

### List 
* list item 1
  * list item 1.1
    * list item 1.1.1
  * list item 1.2
* list item 2

### Table

| item 1 | item 2 | item 3 | item 4 |
|--------|--------|--------|--------|
| 10     |  20    | 30     |  40    |
| 20     |  40    | 10     |  20    |

### Code block
```python
reduce(lambda x, y: x * y, range(1, n+1))
```

### Math

$$ \sum_{k=1}^\infty \frac{1}{k^2} = \frac{\pi^2}{6} $$

$$4+2 = 6$$

### Image

<figure>
  <img src="{{ '/assets/images/your-teaser-image.png' | relative_url }}" alt="indented paragraph example">
  <figcaption>Example of including an image.</figcaption>
</figure>

### Video

{% raw %}{% include video id="6YLMWU-5H9o" provider="youtube" %}{% endraw %}
~~~
