# Jekyll Leabs Theme

![TeXt Theme](/assets/screenshots/theme-shot-1.png)

A simple, clean, responsive Jekyll theme for a blog or personal website.

## Features

Search, comments, pagination, and more. See the [demo](https://jekyll-theme.vercel.app/) for a live look around.

## Installation

1. Fork the repository
2. Edit `_config.yml` to personalize your site.
3. Replace `favicon.ico` with your own.
4. Replace `assets/images/logo.png` with your own.

## Adding Posts

1. Add a new posts to the `_posts` directory.
2. Add the following to the page's front matter:

```
---
layout: post
title: "Post title"
date: 2023-01-21 07:35:33 -0500
comments: true
---
```

## Adding Pages

1. Add a new page to the `root` directory.
2. The Page will automatically be added to the navigation.
3. Add the following to the page's front matter:

```
---
layout: page
title: About
subtitle: Learn more about me
permalink: /about/
comments: false
---
```

## Options

Exclude a page from the navigation using the `exclude` option in the page's front matter:

```
exclude: true
```

The index page is set to `exclude: true` by default as it is hard coded into the navigation.

## RSS Support

RSS support is built in, just navigate to /feed.xml.

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/leabs/jekyll-leabs-theme](https://github.com/leabs/jekyll-leabs-theme)
