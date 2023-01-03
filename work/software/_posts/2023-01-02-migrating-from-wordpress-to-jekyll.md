---
title: 'Migrating from Wordpress.com to Jekyll / Github Pages'
date: '2023-01-01T22:38:00+00:00'
layout: post
---

This site was migrated from a Wordpress.com hosted blog to a Jekyll static site hosted at GitHub Pages and fronted by CloudFlare CDN. Here are some notes:
* The conversion from Wordpress.com to Jekyll is not foolproof. I tried both the "jekyll import" command and copying the blog to a local environment then using the Jekyll Export plugin for WP. In the end both approaches produced data which I combined together in Jekyll.
* A lot of extra garbage was exported/imported from Wordpress. That was removed manually.
* Special shortcodes for Wordpress (such as child page lists and recipes) had to be recreated manually using Liquid constructs. For child page lists, I ended up using page tags and for recipes manual markdown.