---

permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html

---

My research asks how language models represent and generalize linguistic knowledge. I work on linguistic generalization and interpretability of language models and on AI for education, with applications to other areas of applied machine learning.

I am a postdoctoral researcher at the [Language & Knowledge Intelligence Lab](https://lki.ewha.ac.kr/) at Ewha Womans University (PI: Professor Hyunsoo Cho). I received my Ph.D. in Artificial Intelligence from Kyungpook National University in February 2026, advised by Professor Bo-Yeong Kang at the [AIR Lab](https://air.knu.ac.kr/), and then worked as a postdoctoral researcher at the [Energy Storage & System Lab](https://sites.google.com/view/knu2024essl) at KNU.

## News

{% for item in site.data.news limit:5 %}
- **{{ item.date }}** {{ item.text | markdownify | remove: '<p>' | remove: '</p>' | strip }}
{% endfor %}

## Research

**Language models and linguistic generalization.** I study how language models generalize linguistic patterns and how this compares with human language acquisition. Learner language is one testbed, since a writer's native language shapes the variation a model has to handle.

**AI for education.** I build and analyze LLM-based tutoring systems. PATS (Pedagogical Knowledge-Augmented Prompting) infers a learner's mastery and behavioral tendencies from dialogue history and uses them to select teaching strategies for response generation. I also analyze how LLMs judge student misconceptions in science education.

**Applied AI.** I apply AI and machine learning to scientific and interactive systems, including battery diagnostics from microscopy images under domain shift and limited data, and robot learning from human feedback.

## Background

I studied English Education at Kyungpook National University before moving into Artificial Intelligence. My master's research was on interactive reinforcement learning from human feedback, and my doctoral research on learner modeling and intelligent tutoring systems.

## Research Interests

Natural Language Processing · Language Models · Linguistic Generalization · Interpretability · AI for Education · Applied AI

---

**Contact**: hijeon(at)ewha(dot)ac(dot)kr
