---
permalink: /
title: "Hope McGovern"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year Computer Science PhD student and [Woolf Institute Scholar](https://www.woolf.cam.ac.uk/people/hope-mcgovern) at the University of Cambridge. Previously, I was a [Fulbright Scholar](https://fulbrightscholars.org/) in Austria, working in Applied Physics, before I jumped ship to NLP. I hold an MPhil (Master's) in Computer Science from Cambridge, and an Sc.B. (Bachelor's) in Engineering Physics from Brown University.

My research focus is understanding how narratives communicate meaning through reused symbols and structures. Deep learning plays a prominent role in my work, both in surfacing underexplored narrative patterns like [type-scene](https://aclanthology.org/2024.ml4al-1.26/) and [chiasmus](https://arxiv.org/abs/2501.10739), as well as characterizing how well rhetorical structures are maintained in [translation](https://arxiv.org/abs/2501.10731). My work is deeply influenced by Marvin Minksy's [Frame Theory of Knowledge](https://courses.media.mit.edu/2004spring/mas966/Minsky%201974%20Framework%20for%20knowledge.pdf) and Robert Alter's [The Art of Biblical Narrative](https://en.wikipedia.org/wiki/The_Art_of_Biblical_Narrative). Research questions that interest me tend to touch natural language generation (NLG), machine translation (NMT), AI explainability, and [narrative theory](https://aclanthology.org/2021.emnlp-main.26/).

I am looking for a full-time industry position in London after I finish my PhD in the Spring of 2025! You can see my full [CV](https://www.canva.com/design/DAGXlIu9WP4/9ZzHRbzJ6fWK5foUnz7URg/view?utm_content=DAGXlIu9WP4&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h07703e10f1) here.

During my PhD, I've been an intern at Grammarly, working with [Dimi Alikaniotis](https://scholar.google.gr/citations?user=8ZsPobcAAAAJ&hl=en) and [Yoshi Suhara](https://yoshi-suhara.com/) on LLM-generated text detection with stylometrics [[paper link](https://aclanthology.org/2025.genaidetect-1.6/)], and a Research Scholar at the Summer Camp for Applied Language Exploration (SCALE) at the Johns Hopkins [Human Language Technology Center of Excellence](https://hltcoe.jhu.edu/). 


### Beyond Academics
I'm only one country away from completing the '30 countries by 30' challenge! I think #30 will be Wales.

I collect folk instruments from places I travel and learn to play at least one song on each. Perhaps my favourite collected item is an [Appalachian  dulcimer](https://www.youtube.com/watch?v=rZWZ7KpB5Zg) from North Carolina.

As an undergraduate, I wrote for, photographed for, and was Chief Copy Editor of a student-run literary arts magazine called 'Cornerstone'. I'm most proud of [this creative non-fiction piece](https://viewer.joomag.com/wanderers-spring-2017/0019178001494728390/p18) musing about my favourite concept from physics: entropy.



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


