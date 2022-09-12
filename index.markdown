---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
---

Hi! I'm a PhD student at the Language Technologies Institute in the School of Computer Science at Carnegie Mellon. I'm broadly interested in natural language processing, machine learning, and program synthesis, especially in how these fields interact with linguistics and cognitive science.

I completed my undergraduate and masters degrees at [IIIT Hyderabad](https://www.iiit.ac.in/) studying computer science and computational linguistics.  I worked on program synthesis for linguistic rules for my masters thesis, advised by [Monojit Choudhury](https://www.microsoft.com/en-us/research/people/monojitc/) and [Dipti Misra Sharma](https://www.iiit.ac.in/people/faculty/dipti/). I also spent the summer of 2021 as an intern at [Chandar Research Lab](https://chandar-lab.github.io/) at [Mila](https://mila.quebec/en/) working on continual learning for dialogue systems with [Sarath Chandar](http://sarathchandar.in/), [Prasanna Parthasarathi](https://www.cs.mcgill.ca/~pparth2/) and others. I also work with [Evan Pu](https://evanthebouncy.github.io/) and others on making program synthesis more pragmatic.

Feel free to get in touch if you want to chat about research! If you're looking to apply to PhD programs in NLP, check out <a href="/phd-applications">this page</a>!

<h3>News</h3>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 5 %}
{% include news.html news=news %}

<h3>Publications</h3>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}
