---
title: Work / Misc
layout: page
---

This section contains various technology related articles I have written that don’t fit anywhere else.

<span style="text-decoration:underline;">**Articles published via my website:**</span>

<ul>
{% for post in site.categories.misc %}
      <li><a href="{{ post.url }}">
          {{ post.title}} ({{ post.date | date: "%-d %B %Y"}})
      </a></li>
{% endfor %}
</ul>

**<span style="text-decoration:underline;">Articles written by me but published elsewhere:</span>**

- “[Oil Change for Your Computer](/assets/pdf/2016/07/2009-09-10-www-article.pdf "Oil Change for Your Computer")“, Where What When (Baltimore, MD); October 2009 / Vol 25, Issue 3
- “The Browser Wars are Back”; OperaWatch.com; September 2nd, 2008 – [archived copy available](http://wayback.archive.org/web/*/http://operawatch.com/news/2008/09/the-browser-wars-are-back.html) at the Internet Archive
- “Is Opera Facing a Patent Lawsuit?”; OperaWatch.com; July 7th, 2006 – [archived copy available](http://wayback.archive.org/web/*/http://operawatch.com/news/2006/07/is-opera-facing-a-patent-lawsuit.html) at the Internet Archive
- “Opera or Firefox?”; OperaWatch, January 13th, 2005 – [archived copy available](https://web.archive.org/web/20050317233414/http://operawatch.blogspot.com/2005/01/opera-or-firefox.html) at the Internet Archive
- “[A Brief Study of Patent # 6,101,482 and Its Impact on Universal Shopping Cart and Product Comparison Technologies Used on the Internet](/assets/pdf/2016/01/patent.pdf)“, SolidMatrix Technologies, Inc.; July 5th, 2001