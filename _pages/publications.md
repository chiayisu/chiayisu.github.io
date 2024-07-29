---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if author.googlescholar %}
  Pre-prints and more non <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

### **2024**
**C. Su**, A. Bansal, C. McMillan, "Revisiting File Context for Source Code Summarization", in Automated Software Engineering Journal ([ASE Journal](https://link.springer.com/journal/10515)), Volume 31, article 62, 2024, [[arXiv]](https://arxiv.org/abs/2309.02326)

**C. Su** and C. McMillan, "Semantic Similarity Loss for Neural Source Code Summarization", in Journal of Software Evolution and Process (JSME), accepted, 2024. [[arXiv]](https://arxiv.org/abs/2308.07429) [[Code]](https://github.com/apcl-research/funcom-useloss) [[Data/Model]](https://huggingface.co/apcl)

**C. Su** and C. McMillan, "Distilled GPT for Source Code Summarization", in Automated Software Engineering Journal ([ASE Journal](https://link.springer.com/journal/10515)), Volume 31, article 22, 2024. [[arXiv]](https://arxiv.org/abs/2308.14731) [[Code]](https://github.com/apcl-research/Jam-CGPT) [[Data/Model]](https://huggingface.co/apcl)

### **2023**

**C. Su**, A. Bansal, V. Jain, S. Ghanavati, C. McMillan, "A Language Model of Java Methods with Train/Test Deduplication", in 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering, Tool Demos ([ESEC/FSE '23](https://2023.esec-fse.org/track/fse-2023-demonstrations?)),  San Francisco, California, USA, December 3-9, 2023. [[arXiv]](https://arxiv.org/abs/2305.08286) [[Code]](https://github.com/apcl-research/jam) [[Data and Model]](https://huggingface.co/apcl)

A. Bansal, **C. Su**, Z. Karas, Y. Zhang, Y. Huang, T. Li, C. McMillan, "Modeling Programmer Attention as Scanpath Prediction", in 38th IEEE/ACM International Conference on Automated Software Engineering, New Ideas and Emerging Results ([ASE'23 NIER](https://conf.researchr.org/home/ase-2023)), September 11 - 15, 2023. [[arXiv]](https://arxiv.org/abs/2308.13920) [[Code]](https://github.com/apcl-research/scanpathpred)

### **2022**

D. Wang, T. Chen, **C. Su**, AidIR: An Interactive Dialog System to Aid Disease Information Retrieval, Applied Sciences, 12(4), 2022. [[Paper]](https://www.mdpi.com/2076-3417/12/4/1875) [[Data]](https://github.com/chiayisu/ABERT_Corpus)


{% comment %} 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}
