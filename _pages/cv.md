---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Junteng Liu

First-year PhD candidate, HKUST NLP Group  
Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk) · GitHub: [Vicent0205](https://github.com/Vicent0205) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate) · X: [@junteng88716710](https://x.com/junteng88716710)

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present
  - HKUST NLP Group
  - Supervisor: Professor Junxian He
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024
  - Graduated in June 2024
  - Professor Junxian He previously advised Junteng Liu during undergraduate studies at SJTU.

## Research Experience

- **Research Intern**, MINIMAX, February 2025–Present
- **Research Intern**, Tencent WXG, June 2024–September 2024
  - Advisor: Zifei Shan
- **Research Intern**, Shanghai AI Lab, June 2023–December 2023
  - Advisor: Professor Yu Cheng

## Honors and Awards

- **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University

## Skills and Research Expertise

- Natural language processing
- Machine learning
- LLM reasoning
- Reinforcement learning
- Hallucination in vision-language models (VLMs)
- LLM truthfulness
- Model interpretability

## Publications

{% assign cv_publications = site.publications | sort: "order" %}
<ul class="publication-list">
  {% for post in cv_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

The same entries are grouped by publication type on the [Publications page]({{ '/publications/' | relative_url }}) and listed with full author information on the [About page]({{ '/' | relative_url }}#publications).

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [https://github.com/Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Publication profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://x.com/junteng88716710)
