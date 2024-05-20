---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
---

Hi! I'm a PhD student at the Language Technologies Institute in the School of Computer Science at Carnegie Mellon working with [Daniel Fried](https://dpfried.github.io/). I like to think about how we can communicate with machines using natural language, code, demonstrations, and other means to specify the tasks we want them to do. I'm also broadly interested in natural language processing, machine learning, and program synthesis, especially in how these fields interact with linguistics and cognitive science. 

I completed my undergraduate and master's degrees at [IIIT Hyderabad](https://www.iiit.ac.in/) studying computer science and computational linguistics, advised by [Monojit Choudhury](https://www.microsoft.com/en-us/research/people/monojitc/) and [Dipti Misra Sharma](https://www.iiit.ac.in/people/faculty/dipti/). I have spent at [Chandar Research Lab](https://chandar-lab.github.io/) at [Mila](https://mila.quebec/en/) (with [Sarath Chandar](http://sarathchandar.in/) and [Prasanna Parthasarathi](https://www.cs.mcgill.ca/~pparth2/)).

Feel free to get in touch if you want to chat about research! If you're looking to apply to PhD programs in NLP or ML, I <a href="/annotated-sop">annotated my statement of purpose</a> with the ideas and reasoning that went behind it in the hope that it will demystify the process for others. Check it out along with other resources at <a href="/phd-applications">this page</a>!

<h3>News</h3>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 5 %}
{% include news.html news=news %}

<h3>Publications</h3>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}
