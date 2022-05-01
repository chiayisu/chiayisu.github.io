---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
\* indicates corresponding author
### Journal article

Da-Jinn Wang, Tsong-Yi Chen, **Chia-Yi Su\***, AidIR: An Interactive Dialog System to Aid Disease Information Retrieval, Applied Sciences, 12(4), 2022. [[Paper]](https://www.mdpi.com/2076-3417/12/4/1875) [[Data]](https://github.com/chiayisu/ABERT_Corpus) [[bibtex]](../files/bibtex/aidir.bib)


{% comment %} 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}
