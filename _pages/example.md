---
layout: single
title: "Example Page"
permalink: /example/
author_profile: true
toc: true
toc_label: "Contents"
---

## Overview
This is a sample page created with the Minimal Mistakes Jekyll theme. This front matter section (between the `---` markers) contains metadata that Jekyll uses to render your page.

## Key Features

### What's in the Front Matter?
- **layout**: Determines how the page is displayed (use `single` for individual pages)
- **title**: The page title displayed at the top
- **permalink**: Custom URL for the page (e.g., `/example/`)
- **author_profile**: Shows your author info from `_config.yml` on the sidebar
- **toc**: Generates a table of contents from headings
- **toc_label**: Custom label for the TOC

### Content Structure
You can use standard Markdown formatting:

**Bold text** and *italic text* and `inline code`

```python
# Code blocks with syntax highlighting
def hello_world():
    print("Hello, World!")
```

### Lists
Unordered list:
- Item 1
- Item 2
- Item 3

Numbered list:
1. First item
2. Second item
3. Third item

## Optional Front Matter

For more advanced features, you can add:

```yaml
---
layout: single
title: "My Research"
permalink: /research/
author_profile: true
excerpt: "A brief description shown in listings"
toc: true
toc_sticky: true  # Makes TOC stick when scrolling
date: 2024-04-10
last_modified_at: 2024-04-10
categories:
  - Research
tags:
  - Machine Learning
  - AI
header:
  overlay_image: /assets/images/header.jpg
  overlay_filter: 0.5
  caption: "Image credit: Unsplash"
---
```

## Tips

1. **Use consistent heading levels** - Start with `##` (h2) since `#` is reserved for the page title
2. **Add excerpts** - Use `excerpt` for preview text in listings
3. **Use tags/categories** - Organize your content
4. **Tables work great**:

| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |

5. **You can use HTML** - Minimal Mistakes doesn't restrict HTML elements

---

This is your template! Copy the front matter and modify the content sections to create new pages.
