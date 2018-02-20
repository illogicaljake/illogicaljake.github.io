---
layout: page
title: About This Site
slug: meta
permalink: /meta/
---

## Curious how I put this site together?

First of all, check out the code directly in the repo!

This little collection of webpages was developed in about eight hours over a weekend. It's hosted on the
 [Github Pages](https://pages.github.com) platform, which allows any public repository to become a hosted
 website.
 
The site is built with Jekyll and the structure can be broken up like this:

- `_data` includes YML-formatted data that populates some of these pages.
- `_includes` are my mostly-global elements like Header and Footer.
- `_layouts` are the _Liquid_ template files that house the content of the pages.
- `_sass` contains the .scss stylesheets that are compiled on build.
- `_pages` houses markdown files that make up the core content of the site.

For my local development, I have Apache running on my iMac and _PHPStorm_ as my IDE. 

## The Style

With visual details, I often find myself tinkering until perfection. Unfortunately, that means I'm never finished!
For this site, I stuck with default Bootstrap 4 styles while mixing my own flair in every now and then. It's nothing to
write home about, but it serves its purpose while being very lightweight.

I worked with colors from Google's beautiful Material Design library.

The font-stack is comprised of system default fonts, so the most ideal font for any device is used (and it doesn't
hurt load time, too!) Check it out below:

```css
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
```


