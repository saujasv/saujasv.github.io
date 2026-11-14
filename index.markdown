---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
---

Hi! I'm a PhD candidate at the Language Technologies Institute in the School of Computer Science at Carnegie Mellon working with [Daniel Fried](https://dpfried.github.io/). My research develops methods to train AI agents as collaborators, and evaluate their ability to work with people. My work is supported by the Microsoft Research Fellowship.

I've spent summers as an intern at Microsoft Research working with [Chan Young Park](https://chan0park.github.io/) and [Jennifer Neville](https://jenneville.github.io/), and at the Autodesk AI Lab working with [Evan Pu](https://evanthebouncy.github.io/) and [Will McCarthy](https://wpmccarthy.com/). I completed my undergraduate and master's degrees at [IIIT Hyderabad](https://www.iiit.ac.in/) studying computer science and computational linguistics, advised by [Monojit Choudhury](https://mbzuai.ac.ae/academics/faculty-directory/monojit-choudhury) and [Dipti Misra Sharma](https://www.iiit.ac.in/people/faculty/dipti/). As an undergrad, I interned at [Mila](https://mila.quebec/en/) working with [Sarath Chandar](http://sarathchandar.in/) and [Prasanna Parthasarathi](https://www.cs.mcgill.ca/~pparth2/).

Feel free to get in touch if you want to chat about research! If you're looking to apply to PhD programs in NLP or ML, I <a href="/annotated-sop">annotated my statement of purpose</a> with the ideas and reasoning that went behind it in the hope that it will demystify the process for others. Check it out along with other resources at <a href="/phd-applications">this page</a>!

<h3>News</h3>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 5 %}
{% include news.html news=news %}

<h3>Publications</h3>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}
