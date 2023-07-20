---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
**C. Su**, A. Bansal, V. Jain, S. Ghanavati, C. Mcmillan, "A Language Model of Java Methods with Train/Test Deduplication", in 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering, Tool Demos (ESEC/FSE '23),  San Francisco, California, USA, December 3-9, 2023. [[Paper]](https://arxiv.org/abs/2305.08286)

A. Bansal, **C. Su**, Z. Karas, Y. Zhang, Y. Huang, T. Li, C. McMillan, "Modeling Programmer Attention as Scanpath Prediction", in 38th IEEE/ACM International Conference on Automated Software Engineering, New Ideas and Emerging Results (ASE'23 NIER), September 11 - 15, 2023.

D. Wang, T. Chen, **C. Su**, AidIR: An Interactive Dialog System to Aid Disease Information Retrieval, Applied Sciences, 12(4), 2022. [[Paper]](https://www.mdpi.com/2076-3417/12/4/1875) [[Data]](https://github.com/chiayisu/ABERT_Corpus) [[bibtex]](../files/bibtex/aidir.bib)


{% comment %} 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}
