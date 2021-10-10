---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Publications (Chinese)

[1]	Da-Jinn Wang, Tsong-Yi Chen, **Chia-Yi Su**, “MedBERT: 基於BERT語言模型的中文醫學文本理解研究” [MedBERT: Chinese Medical Document Classification Based on BERT Language Model], Symposium on Digital Life Technologies (DLT-2021), Pingtung, Taiwan, R.O.C. May 14-15, 2021.

[2]	Tsong-Yi Chen, **Chia-Yi Su**, Da-Jinn Wang, Mong-Fong Horng , “中文自然語言對話系統—以豬隻疾病諮詢問答服務為例” [A Dialog System for Swine Disease Consultation in Chinese Language], 2020 Workshop on Consumer Electronics (WCE2020), Kaohsiung, Taiwan, R.O.C. pp. 484-489, December 11, 2020. (Best Presentation Award)


{% comment %} 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}
