---
title: Work / Cybersecurity
layout: page
tags: work
---

I contribute to research and do contract work but most of that work is not available publicly due to contractual obligations. Most of my public cybersecurity work is being published [on the Nightwatch Cybersecurity Blog here](https://wwws.nightwatchcybersecurity.com/blog/).

*(Anti-spam work can be found [here](/work/anti-spam/), Internet standards work can be found [here](/work/internet-standards/).)*

<span style="text-decoration:underline;">**Articles written by me but published elsewhere:**</span>

- “[Bluetooth Data Exchange Between Android Phones Without Pairing](http://arxiv.org/abs/1507.00650)” (non-peer reviewed paper); Arxiv.org; July 2nd, 2015; see also [my blog post at Noom’s engineering blog](https://www.noom.com/engineering-blog/2015/07/bluetooth-data-exchange-between-android-phones-without-pairing/)
- **“Overview of Technical Measures for Safer Internet Browsing”**; research report for [Technology Awareness Group (TAG)](http://www.taghelpline.org/); January 2010
- [“ICANN Transfer Policy: Domain Hijacking Got Easier or Did It?”](https://circleid.com/posts/icann_transfer_policy_domain_hijacking_got_easier_or_did_it); Circle-ID, November 10th, 2004

<span style="text-decoration:underline;">**Articles published via my website:**</span>

<ul>
{% for post in site.categories.cybersecurity %}
      <li><a href="{{ post.url }}">
          {{ post.title}} ({{ post.date | date: "%-d %B %Y"}})
      </a></li>
{% endfor %}
</ul>