# Hexo PaperMod Theme

A port of the [Hugo PaperMod theme](https://github.com/adityatelange/hugo-PaperMod) for Hexo.

## Features

- Responsive design
- Light/Dark mode toggle
- Table of Contents
- Social icons
- Share buttons
- Cover images
- Archive view
- Tags and Categories support
- Search functionality
- Pagination
- Multilingual support
- Code highlighting
- And more!

## Installation

1. Download or clone this repository
2. Place it in your Hexo site's `themes` directory
3. Update your Hexo site's `_config.yml` to use the theme:

```yaml
theme: papermod
```

## Configuration

Edit your theme's `_config.yml` file to customize the theme:

```yaml
# Theme Information
theme_name: PaperMod
version: 1.0.0
description: A fast, clean, responsive Hexo theme based on Hugo PaperMod

# Features
features:
  darkmode: true
  search: true
  toc: true
  cover_image: true
  social_icons: true
  share_icons: true
  archive: true
  multilingual: true
  theme_toggle: true
  scroll_to_top: true

# Menu Configuration
menu:
  Home: /
  Archives: /archives/
  Categories: /categories/
  Tags: /tags/
  Search: /search/

# Social Icons
social:
  - icon: github
    url: https://github.com/
    title: GitHub
  - icon: twitter
    url: https://twitter.com/
    title: Twitter
  - icon: rss
    url: /atom.xml
    title: RSS

# Default cover image
defaultCover: /img/default-cover.jpg

# Site Settings
showReadingTime: true
showShareButtons: true
showPostNavLinks: true
showBreadCrumbs: true
showCodeCopyButtons: true
disableSpecial1stPost: false
disableScrollToTop: false
comments: false
hidemeta: false
hideSummary: false
showtoc: true
tocopen: false

# Internationalization
defaultContentLanguage: en
```

## Post Front Matter

Example front matter for posts:

```yaml
---
title: Your Post Title
date: 2025-05-29
tags:
  - tag1
  - tag2
categories:
  - category1
cover: /path/to/cover-image.jpg
toc: true
---
```

## Credits

- Original [Hugo PaperMod theme](https://github.com/adityatelange/hugo-PaperMod) by Aditya Telange
- Converted to Hexo by Manus AI
