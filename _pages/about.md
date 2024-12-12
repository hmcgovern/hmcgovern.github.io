---
permalink: /
title: "Hope McGovern"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year Computer Science PhD student and [Woolf Institute Scholar](https://www.woolf.cam.ac.uk/people/hope-mcgovern) at the University of Cambridge. Previously, I was a [Fulbright scholar](https://fulbrightscholars.org/) in Austria, applying deep learning to superresolution microscopy. I hold an MPhil in Computer Science from Cambridge, and an Sc.B. in Engingeering Physics from Brown University.

My research interests lie in story understanding, natural language generation, and multilingual NLP. My PhD thesis focus is on structure-aware analysis of historical religious texts. I am looking for a full-time position in London after I finish my PhD in Spring 2025.

I was recently an intern at Grammarly, working with [Dimi](https://scholar.google.gr/citations?user=8ZsPobcAAAAJ&hl=en) and [Yoshi](https://yoshi-suhara.com/), and a Research Scholar at the Summer Camp for Applied Language Exploration (SCALE) at the Johns Hopkins [Human Language Technology Center of Excellence](https://hltcoe.jhu.edu/). 


### Beyond Academics
I'm only one country away from completing the '30 countries by 30' challenge! I think #30 will be Wales.

I collect folk instruments from places I travel and learn to play at least one song on each. Perhaps my favourite collected item is an [Appalachian  dulcimer](https://en.wikipedia.org/wiki/Appalachian_dulcimer) from North Carolina.

As an undergraduate, I wrote for, photographed for, and was Chief Copy Editor of a student-run literary arts magazine called 'Cornerstone'. I'm most proud of [this creative non-fiction piece](https://viewer.joomag.com/wanderers-spring-2017/0019178001494728390/p18) musing about my favourite concept from physics -- entropy.



<div class="news-widget">
    <h2>Latest News</h2>
    <ul>
        {% for post in site.posts limit:10 %}
            <li>
                <strong>{{ post.title }}</strong> | <small>{{ post.date | strip_newlines | date: "%B %d, %Y" }}{{ post.location | strip_newlines }}</small> | {{ post.excerpt | strip_newlines | markdownify }} 
            </li>
        {% endfor %}
    </ul>
</div>


