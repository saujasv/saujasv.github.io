---
layout: archive
title: Curriculum Vitae
permalink: /cv/
---

<a href="/assets/Saujas-Vaduguru-CV.pdf"><i class="fa-solid fa-file-pdf"></i> View PDF</a><br>
<a href="https://saujasv.github.io/"><i class="fa-solid fa-globe"></i> saujasv.github.io</a><br>
<a href=""><i class="fa-solid fa-envelope"></i> svadugur [AT] cs [DOT] cmu [DOT] edu</a><br>
<a href="https://github.com/saujasv"><i class="fa-brands fa-github"></i> saujasv</a>


<h2>Education</h2>
{% include cv_item.html
    margin='Starting 2022'
    main='<strong>Ph.D. in Language and Information Technologies</strong><br>
    <em>Language Technologies Institute, School of Computer Science, Carnegie Mellon University</em>'
%}

<!-- <br><span class="small-caps">Advisor:</span> Daniel Fried' -->

{% include cv_item.html
    margin='2017–2022'
    main='<strong>B.Tech. in Computer Science</strong> and <strong>M.S. (by Research) in Computational Linguistics</strong><br>
    <em>International Institute of Information Technology (IIIT), Hyderabad</em>
    <br><span class="small-caps">Advisors:</span> Monojit Choudhury, Dipti Misra Sharma<br>
    <span class="small-caps">Thesis:</span> Program Synthesis for Linguistic Rules'
%}

<h2>Former Positions</h2>
{% include cv_item.html
    margin='2019–2022'
    main='<strong>Research Assistant</strong>, Language Technologies Research Center, <em>IIIT, Hyderabad</em><br>
    <ul>
    <li>Developed program synthesis methods to learn rules for phonological stress placement from a small number of examples</li>
    <li>Designed various domain-specific languages to compare impact of specifying linguistic knowledge explicitly</li>
    <li style="list-style-type:none"><span class="small-caps">Skills:</span> C#, Python, Microsoft <span class="small-caps">prose</span> SDK</li>
    </ul>'
%}

{% include cv_item.html
    margin='May–Aug 2021'
    main='<strong>Research Intern</strong>, Chandar Research Lab, <span class="small-caps"><em>Mila</em></span><br>
    <span class="small-caps">Advisors:</span> Sarath Chandar, Prasanna Parthasarathi<br>
    <ul>
    <li>Explored slot-incremental continual learning set-ups in dialogue state tracking (DST)</li>
    <li>Finetuned Transformer-based models for DST using various continual learning algorithms</li>
    <li style="list-style-type:none"><span class="small-caps">Skills:</span> Python, PyTorch, HuggingFace Transformers</li>
    </ul>'
%}

<h2>Publications</h2>
{% include publications.html
    publications=site.data.publications
    numbering=true
%}

<h2>Honors and Awards</h2>
{% include cv_item.html
    margin='2021'
    main='<span class="small-caps">Mitacs</span> Globalink Research Internship'
%}

{% include cv_item.html
    margin='2017–2021'
    main='Dean\'s List Award for Academic Performance, IIIT Hyderabad'
%}

{% include cv_item.html
    margin='2015'
    main='Honourable Mention, International Linguistics Olympiad'
%}

<h2>Academic Service</h2>
{% include cv_item.html
    margin='<span class="small-caps">Reviewer</span>'
    main='ICON 2021, NILLI@EMNLP 2021'
%}

<h2>Teaching</h2>
{% include cv_item.html
    margin='Spring 2020'
    main='<strong>Teaching Assistant</strong>, Computational Linguistics I, IIIT Hyderabad'
%}

<h2>Outreach</h2>
{% include cv_item.html
    margin=''
    main='<strong>Panini Linguistics Olympiad</strong><br>
    <ul>
    <li>Co-chair of Problem Committee and Jury, and member of the Organizing Committee for the Indian national Linguistics Olympiad program from 2018–2021 </li>
    <li>Team leader and coach for Indian team at the International Linguistics Olympiad in 2018, 2019, and 2021</li>
    <li>Lecturer at Joint Asian-Pacific Linguistics Training, 2021</li>
    </ul>'
%}