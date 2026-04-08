---
permalink: /
title: "Hi, I'm Miriam!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<br>
I'm currently a Visiting Postdoc at the [Digital Emotions Lab](https://www.amitgoldenberg.com) at Harvard Business School.

I develop computational approaches to analyze potentially harmful content online, such as **violent language and abusive behavior**. I analyze large-scale text data with **Natural Language Processing (NLP)**, identify patterns, and combine these with **experimental studies** to see how we can connect results from language models with real-world behavior. 

My current projects focus on 
- understanding how people interact with information that attacks scientists online, 
- child safety on TikTok, and
- validating online harm detection with psychological assessment (for instance, if we detect hate speech, do people actually feel bad when they read it?)

I was previously a postdoctoral researcher at [LINK Lab](https://link.soc.northwestern.edu/about-us/) at **Northwestern University***.
I received my PhD from **Technical University of Munich** ([Computational Social Science Lab](https://www.hfp.tum.de/css/startseite/)). I hold three undergraduate degrees in Psychology, Political Science, and History, and a master’s degree in Criminology.

I have been a visiting researcher at **University of Michigan**, **University of Cambridge**, and the **Auschwitz Institute** for the Prevention of Mass Atrocities in New York City.

Updates
------

{% for update in site.data.updates limit:5 %}
{{ update.date }}<br>
{{ update.content }}

{% endfor %}
[...](/updates/)




Selected Publications
------

{% assign featured_pubs = site.data.publications | where: "featured", true %}
{% for pub in featured_pubs %}
- **[{{ pub.title }}]({{ pub.url }})**<br>
  {{ pub.authors }} ({{ pub.year }})<br>
  {{ pub.venue }}
{% endfor %}

[See all publications](/publications/)

------

Talks
------

{% for talk in site.data.talks limit:5 %}
- {{ talk.authors }} ({{ talk.date }}). *{{ talk.title }}.* {{ talk.venue }}.
{% endfor %}

[...](/talks/)


About Me
------

If I were to visit your city, you'd find me exploring a local bookshop for my next book club pick, then settling into a cozy coffee shop, or joining a salsa or bachata social.

I'm one of the deputy chairs at [Genocide Alert](https://www.genocide-alert.de/about/), a German human rights organization that advocates for the effective prevention and punishment of grave human rights violations such as genocide and crimes against humanity.

My work and studies have been supported by the [German Academic Scholarship Foundation](https://www.studienstiftung.de/en/), the [German Business Foundation](https://www.sdw.org), and the [Bavarian Research Institute for Digital Transformation](https://en.bidt.digital).