---
layout: post
title: "Using Images in Jekyll Blog Posts"
date: 2024-12-07 12:00:00 -0000
categories: tutorial
---

This post demonstrates how to include images in your Jekyll blog posts. Here are the different ways you can add images:

## 1. Basic Markdown Image

```markdown
![Alt text](/assets/images/posts/2024/sample-image.jpg)
```

## 2. HTML Image with Custom Sizing

```html
<img src="/assets/images/posts/2024/sample-image.jpg" alt="Alt text" width="600">
```

## 3. Project Images

For project-related images, use the projects directory:

```markdown
![Project screenshot](/assets/images/projects/project-screenshot.png)
```

## Tips for Using Images

1. Always include descriptive alt text
2. Use appropriate image formats:
   - JPG for photographs
   - PNG for screenshots
   - SVG for logos and icons
3. Optimize images before uploading
4. Use relative paths starting with `/assets/images/`

## Image Organization

Your blog now has the following image directories:

- `/assets/images/posts/2024/` - For blog post images
- `/assets/images/projects/` - For project screenshots and images
- `/assets/images/site/` - For site-wide images like logos

Choose the appropriate directory based on your image's purpose.
