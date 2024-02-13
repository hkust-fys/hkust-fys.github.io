---
layout: post
title: Format Specification
---

This format specification describes the _technical_ format of each file type. It does not specify the content formatting, style, and others, which is instead described in the [Manual of Style](Manual_of_Style.md).

## Pages

All pages must use Markdown. Their file extension must be `.md`.

All pages must start with a frontmatter, containing the following two properties:

```Markdown
---
layout: layout value
title: title value
---
```

The properties must be ordered by their key names alphabetically. Additional properties can be added.

For `layout value`, it must be `post` for all pages except for the homepage, for which it must be `home`. For `title value`, it must be any non-empty string complying with [Title Policy § Titles](title_policy.md#titles).
