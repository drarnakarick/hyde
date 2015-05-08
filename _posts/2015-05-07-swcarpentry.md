---
layout: post
title: Two-day Unix/Python Workshop Wrap-up
---

#### Workshop review
<em>by Arna Karick</em>

Workshop website:  <a href="http://drarnakarick.github.io/2015-05-04-swinpython/">May 4th &amp; 5th 2015</a>

Earlier this week we ran our first two-day Unix/Python workshop for PhD students and research staff interested in getting started with Python. The was led by Swinburne Univeristy's newly minted Software Carpentry instructors, Ewan Barr and Genevieve Shattow, with help from a small team of unix and python experts from the Centre of Astrophysics and Supercomputing.

Since this workshop was designed to teach general python skills participants came from a variety of research disciplines (see below for an interactive profile of participants). Consequently there was a large spread in programming experience and ability (and even operating system). 

We chose to install software locally rather than using a pre-configured cloud instance. While this takes a little more effort it meant that participants could set up their own GitHub accounts, gitbash shell and python (Anaconda) installation for use later on. It also gives them a better understanding of how their laptop operates. Fortunately this went rather smoothly. We anticipated that the first half of the first session would be spent troubleshooting Linux, Windows and Mac OSX issues, but this wasn't case. A few days before the workshop we held an hour long helper meeting where participants could come and get help setting up laptops. This turned out to be a really good idea and we'll definitely be offering that next time. For larger workshops we'll think about setting up a pre-configured instance using NeCTAR's Research Cloud.

The first session on the Unix shell was a little hit and miss I think - mainly because of the material. If you've  used the shell throughout your PhD/postdoc I don't think you get much out of this session, unless you want to brush up on your scripting skills. If you've never used it (or even heard of it) it can be quite baffling. Genevieve did an excellent job teaching this session which is more conceptual, with less guided material than the rest of the workshop. Based on a number of reviews of  Python workshops held at other instutions, a favoured option is to present Unix shell material as optional pre-workshop homework therefore allowing more time for Python and SQL.

Python was our language of choice, because it’s free, intuitive and popular, especially in the physical sciences. It's also a useful (and often expected) language for those who want to move into the tech industry. This did not mean that only Python users (or potential users) would benefit from this particular workshop. Since the focus is on learning general programming skills that are transferable to any language, learning Python basics is a good place to start. We covered the most useful elements of programming; manipulating data, plotting, using loops and conditional statements ("for", "if", "else" etc.) and functions. 

The structure of the workshop was mix og guided teaching with challenges thrown in along the way. Participants were encouraged to work in small groups and discuss ideas.  Of course we spent more time on each session than originally planned, but this seems to be typical of Software Captentry courses - too much (great!) material, too little time. 

#### Lesson Plans

Below are the detailed lesson plans for researchers and PhD students wishing to go through the course again in their own time. Simply open up a terminal and launch Python or iPython notebook. If you have forgotton what was installed or how to launch programs review the [setup and testing notes](http://drarnakarick.github.io/2015-05-04-swinpython/setup/index.html). 

* Unix shell lesson plan: [shell-novice](http://swcarpentry.github.io/shell-novice/).
* Python lesson plan: [python-novice-inflammation](http://swcarpentry.github.io/python-novice-inflammation/).
* Version control with git lesson plan: [git-novice](http://swcarpentry.github.io/git-novice/).

Also, here are few short presentations about the Unix shell, Python and version control, and the motivation for teaching them.

* [Why learn about the unix shell?](http://swcarpentry.github.io/shell-novice/motivation.html)
* [Why learn Python?](http://swcarpentry.github.io/python-novice-inflammation/motivation.html)
* [Why learn about the version control?](http://swcarpentry.github.io/git-novice/motivation.html)

#### Reference Pages

* Unix shell: [reference page](http://swcarpentry.github.io/shell-novice/reference.html), [cheat sheet](http://software-carpentry.org/v5/novice/ref/01-shell.html).
* Python: [reference page](http://swcarpentry.github.io/git-novice/reference.html), [cheat sheet](http://software-carpentry.org/v5/novice/ref/03-python.html).
* Version control - Git: [reference page](http://swcarpentry.github.io/git-novice/reference.html), [cheat sheet](http://software-carpentry.org/v5/novice/ref/02-git.html).


#### Most importantly... keep programming!

* Keep in touch with your fellow workshop participants. 
* Practise by working on small programs/data analysis with researchers in your own group/field.
* Attend the next Software Carpentry workshop (at Swinburne or Melbourne Uni).
* Come along to [Swinburne Hacker Within](http://thehackerwithin.github.io/swinburne/) and start a project using your Python skills.
* Network. Meet fellow students and researchers interested in data analysis and visualisation. e-Research Coffee is every Thursday - 3pm at Haddons.

## Some statistics:  

#### Profile of workshop participants

Thirty people attended part or all of the workshop. Roughly half the participants were women, with an even split between PhD students (light grey - outer ring) and established research postdocs and staff (dark grey - outer ring). 

<iframe width="700px" height="700px" src="http://drarnakarick.github.io/software-carpentry-resources/public/participants.html" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

Research Group/Department:

* CAS - Centre for Astrophysics and Supercomputing
* CMP - Centre for Micro-Photonics
* BPsyC - Brain and Psychological Sciences Research Centre
* CHP - Centre for Human Psychopharmacology.
* COEST - Centre for Ocean Engineering, Science and Technology
* SISR - Swinburne Institute for Social Research
* DBHS - Department of Biomedical and Health Sciences
* CTI - Centre for Transformative Innovation
* EBC - Environment and Biotechnology Centre

The script (participants.html) for generating the above plot, and example data (participants_template.csv), can be downloaded from this [resources  repository](http://drarnakarick.github.io/2015-05-04-swinpython/public/participants.csv). The template was provided by [@evilangelpixie](http://twitter.com/evilangelpixie) and is a modified version of the [Sequences Sunburst](http://bl.ocks.org/kerryrodden/7090426) template. 



