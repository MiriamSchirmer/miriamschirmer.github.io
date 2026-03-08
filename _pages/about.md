---
permalink: /
title: "Hi, I'm Miriam!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<br>
I'm a postdoctoral researcher at [LINK Lab](https://link.soc.northwestern.edu/about-us/) at Northwestern University.

I develop computational approaches to analyze potentially harmful phenomena in the online world, such as **misinformation, violent language, and abusive behavior**. I analyze large-scale text data with **Natural Language Processing (NLP)**, identify patterns, and combine these with **experimental studies** to see how we can connect results from language models with real-world behavior.

I received my PhD from **Technical University of Munich** ([Computational Social Science Lab](https://www.hfp.tum.de/css/startseite/)). I hold three undergraduate degrees in Psychology, Political Science, and History, and a master’s degree in Criminology.

During my PhD, I have been a visiting researcher at **University of Michigan**, **University of Cambridge**, and the **Auschwitz Insitute** for the Prevention of Mass Atrocities in New York City.

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
  {% if pub.note %}*{{ pub.note }}*<br>{% endif %}
  {{ pub.venue }}
{% endfor %}

[See all publications](/publications/)

------

Talks
------
- Schirmer, M. (2025, November). *Natural Language Processing for Trauma Detection.* **Human Rights Center, UC Berkeley**.

- Schirmer, M. (2025, October). *Natural Language Processing for Harm Detection and Mitigation.* **CCEW Online Speaker Series**, University of the Bundeswehr Munich.

- Schirmer, M. (2025, July). *Understanding and Reducing the Psychological Impact of Online Harm.* **MilaNLP Seminar, Bocconi University**.

- Schirmer, M. (2025, April). *Sharenting and Child Exposure on TikTok.* **Text-as-Data** ([TaDa](https://sites.google.com/view/polsci-ml-initiative/talks?authuser=0)) **Speaker Series**.

- Schirmer, M. (2025, February). *Natural Language Processing for Objectification Detection.* Information Sciences Institute (ISI), **University of Southern California**.

- Schirmer, M. (2024, May). *Modeling Complex Phenomena Through Language: From Hate Speech to Innovation.* Center for Science of Science & Innovation (CSSI), **Kellog, Northwestern University**.

- Schirmer, M. (2024, April). *Natural Language Processing for Violence Research.* Computational Social Science Seminar, School of Information, **University of Michigan**.

- Schirmer, M., Pfeffer, J., & Kirchmair, T. (2023, September). *Analyzing and Visualizing Criminal Career Trajectories.* **European Conference on Social Networks (EUSN)**. Ljubljana, Slovenia.

- Schirmer, M., & Stewens, P. (2023, July). *Natural Language Processing in Genocide Studies.* **16th Biennial Meeting of the International Association of Genocide Scholars (IAGS)**. Barcelona, Spain.

- Schirmer, M., & Pfeffer, J. (2023, June). *The Genocide Transcript Corpus.* **Conference of the Research Group International Relations of the German Political Science Association**. Friedrichshafen, Germany.

- Schirmer, M. (2023, March). *Mixed Methods in Genocide Research.* **German Digital Humanities Conference (DHd)**. Trier, Germany.

...


About Me
------

If I were to visit your city, you'd find me exploring a local bookshop for my next book club pick, then settling into a cozy coffee shop, or joining a salsa or bachata social.

I'm one of the deputy chairs at [Genocide Alert](https://www.genocide-alert.de/about/), a German human rights organization that advocates for the effective prevention and punishment of grave human rights violations such as genocide and crimes against humanity.

My work and studies have been supported by the [German Academic Scholarship Foundation](https://www.studienstiftung.de/en/), the [German Business Foundation](https://www.sdw.org), and the [Bavarian Research Institute for Digital Transformation](https://en.bidt.digital).