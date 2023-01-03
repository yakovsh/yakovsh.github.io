---
title: Personal / Politics
layout: page
tags: personal
---

I had a brief involvement in local politics, particulary in Baltimore City / State of Maryland around 2007-2014. I also served as a Board member (2011-2014) of the [Fallstaff Improvement Association](http://www.welcometofallstaff.org/), a local neighbourhood association covering Northwest Baltimore and I used to also maintain their website.

Here is a list of articles published by others, that either mention or quote me in some fashion, politics related:

- **“City Employees Do Not Equal City Dwellers”**; Baltimore City Paper; April 11th, 2012
- **[“Shafranovich vs. Baltimore City Environmental Board (ECB)”](https://www.marylandattorneygeneral.gov/Opinions%20OMCB%20Documents/Vol07/7omcb186.pdf)**; Opinion of the Open Meetings Compliance Board of the State of Maryland; 7OMCB186; May 23rd, 2011
- **“Check fine print on phone bill’s energy charge, other new fees”** by Dan Thanh Dang; Baltimore Sun (Baltimore, MD); August 28, 2008
- **“This Phone is Tapped”**; MetroPulse; Knoxville, TN; June 8th, 2006

Here are articles I have written and published via my website,
primarily about local politics in the City of Baltimore and State of Maryland:

<ul>
{% for post in site.categories.politics %}
      <li><a href="{{ post.url }}">
          {{ post.title}} ({{ post.date | date: "%-d %B %Y"}})
      </a></li>
{% endfor %}
</ul>