---
title: "Header video"
author: Dennis Edblom
last_modified_at: 2019-11-07T08:06:00-05:00
header:
  video:
    id: yYAw79386WI
    provider: youtube
---

This post shows how to add a header video. The header video is added in the front matter of the post, for more information on front matter [click here](/frontmatter/).

You need to add the following to your front matter, where you specify the provider and video id. For instance if you want to use a youtube video the provider will be youtube and the id will be found in the link to the video after the '=' sign. In this post the video [https://www.youtube.com/watch?v=yYAw79386WI](https://www.youtube.com/watch?v=yYAw79386WI) is used which have the id: yYAw79386WI. 
```markdown
header:
  video:
    id: yYAw79386WI
    provider: youtube
```

You can also use other providers such as vimeo. For instance if you wanted to use the video [https://vimeo.com/148751763](https://vimeo.com/148751763) then the header tag in the frontmatter would look like this.

```markdown
header:
  video:
    id: 148751763
    provider: vimeo
```

The full front matter of this post is.

```markdown
---
title: "Header video"
author: Dennis Edblom
last_modified_at: 2019-11-07T08:06:00-05:00
header:
  video:
    id: yYAw79386WI
    provider: youtube
---
```