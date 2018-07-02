# AI4India
Using AI for India 

## Usage

### Adding a Post

- Create a markdown file (.md) file in any of the `_posts` directory (choose a sub-directory so that it will be organised). The `.md` file must contain this following front matter

```markdown
---
layout: post
current: post
cover:  <path to image you as the cover image (/assets/images/<image name>)>
navigation: True
title: <Title of the post>
date: <date and time>
tags: <refer _data/tags.yml . Enter the tag which suits you or create a new one>
class: post-template
subclass: 'post tag-getting-started'
author: <refer _data/author.yml . Enter the names which suits you or create a new one>
---
```

Example one

```markdown
---
layout: post
current: post
cover:  assets/images/agriculture.jpg
navigation: True
title: Agriculture
date: 2017-07-27 09:00:00
tags: [Agriculture]
class: post-template
subclass: 'post tag-getting-started'
author: lewis
---
```

Then fill your content. Note that you can use markdown syntax for styling.