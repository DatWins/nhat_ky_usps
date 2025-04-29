---
title: Image Gallery Shortcode
date: 2024-11-20
tags: ["image"]
draft: false
---

Here’s a custom Hugo shortcode that creates an image gallery in a masonry style using GLightbox, allowing you to specify a folder containing images. This approach will display images from a specified folder in a masonry layout, and each image will open in a lightbox when clicked.

**Shortcode**:  
```
{{/*< img_gallery  folder="img/travel/" >*/}}
```

**Output**:
{{< img_gallery  folder="img/travel/" >}}
