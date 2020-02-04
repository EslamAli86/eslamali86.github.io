---
layout: page
title: Eslam Hussein
cover: false
---

Hi, I am Eslam Hussein. I am a PhD student in the department of Computer Science at Virginia Tech. My research interests are in the broad areas of social computing, natural language processing and machine learning. I design experiments and technology to explore the  in which ranking algorithms influence the attitudes, beliefs, and behaviors of individuals and groups. I worked with Robert Epstein to discover the search engine manipulation effect (SEME), conduct research in several psychology-related fields, and build a nonprofit, the American Institute for Behavioral Research and Technology in San Diego, CA. In 2016 I became a student again in the world's first Network Science PhD program at Northeastern University in Boston, MA. Currently, I work with Christo Wilson and David Lazer on reverse engineering ranking algorithms - such as those used by search engines and online marketplaces - and conducting controlled behavioral and computational experiments to analyze their social impact.



I develop computational models of natural language learning, 
understanding and generation in people and machines, and my research 
focuses on basic scientific problems related to these models. I am 
especially interested in modeling the rich diversity of linguistic
phenomena across the world’s languages. 

I am a [Reader](https://en.wikipedia.org/wiki/Reader_(academic_rank))
in the [Institute for Language, Cognition, and Computation](http://web.inf.ed.ac.uk/ilcc)
in the [School of Informatics](http://web.inf.ed.ac.uk/)
at the [University of Edinburgh](https://www.ed.ac.uk/). 
[My research group](collaborators) is part of the larger 
[Edinburgh natural language processing group](http://groups.inf.ed.ac.uk/edinburghnlp/)
and we collaborate with many people in Edinburgh and more widely. 
I am also the co-director of the 
[Centre for Doctoral Training in Natural Language Processing](https://edinburghnlp.inf.ed.ac.uk/cdt/).


## Recent News
* In 2019, five of my PhD students successfully defended their theses:
  - [Sameer Bansal](https://0xsameer.github.io/), whose thesis was on 
    Low-Resource Speech Translation.
  - [Arabella Jane Sinclair](https://staff.fnwi.uva.nl/a.j.sinclair/),
    whose thesis was on Modelling Speaker Adaptation in Second 
    Language Learner Dialogue. 
    She is now a postdoctoral researcher at the University of Amsterdam.
  - [Clara Vania](https://claravania.github.io/), whose thesis was 
    On Understanding Character-level Models for Representing Morphology.
    She is now a postdoctoral researcher at New York University.
  - [Nikolay Bogoychev](https://nbogoychev.com/),
    whose [thesis](https://www.era.lib.ed.ac.uk/handle/1842/35886) 
    was on Fast Machine Translation on Parallel and Massively Parallel 
    Hardware. 
    He is now a postdoctoral researcher at the University of Edinburgh.
  - [Sorcha Gilroy](https://uk.linkedin.com/in/sorcha-gilroy-a6105693), whose 
    [thesis](https://www.era.lib.ed.ac.uk/handle/1842/35606) was on 
    Probabilistic Graph Formalisms for Meaning Representations. 
    She is now a data scientist at Peak.ai.



* In September 2019, the 
[Centre for Doctoral Training in Natural Language Processing](https://edin.ac/cdt-in-nlp)
[welcomed its first students](https://twitter.com/EdinburghNLP/status/1173630819652579338)
The centre, directed by my colleague [Mirella Lapata](http://homepages.inf.ed.ac.uk/mlap/),
is a collaboration between informatics, linguistics, psychology, and design.
It offers an innovative new PhD programme that integrates research and 
teaching across these disciplines, and is supported in part by a 
multi-million pound [training grant from the UK government](https://www.ukri.org/research/themes-and-programmes/ukri-cdts-in-artificial-intelligence/). I am 
the co-director. 

## Recent Research Highlights

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

