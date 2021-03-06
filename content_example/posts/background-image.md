---
layout: post
title: Post with a Background Image
description: "Sample post with a background image CSS override."
tags: [sample post]
date: 2013-10-26
background: /images/triangular.png
share: false
comments: false
draft: true
---

Here be a sample post with a custom background image. To utilize this "feature" just add the following YAML to a post's front matter.

```yaml
background: /images/filename.png
```

This little bit of YAML makes the assumption that your background image asset is in the `/images` folder. If you place it somewhere else or are hotlinking from the web, just include the full http(s):// URL. Either way you should have a background image that is tiled.

If you want to set a background image for the entire site just add `background: /images/filename.png` as a [param](https://gohugo.io/overview/configuration/#examples) in your config and BOOM --- background images on every page!

<div xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/" about="http://subtlepatterns.com" class="notice">Background images from <span property="dct:title">Subtle Patterns</span> (<a rel="cc:attributionURL" property="cc:attributionName" href="http://subtlepatterns.com">Subtle Patterns</a>) / <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a></div>
