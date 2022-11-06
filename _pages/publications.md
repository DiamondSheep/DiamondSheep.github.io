---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br/>

Preprints & Working Papers
======

* Zhao Zhang, **Yangcheng Gao**, et al. "SelectQ: Calibration Data Selection for Post-Training Quantization," submitted to *CVPR*, 2023.

* Yan Luo#, **Yangcheng Gao**#, et al. "Long-Range Zero-Shot Generative Deep Network Quantization," submitted to *CVPR*, 2023.

* **Yangcheng Gao**, Zhao Zhang, et al. "ClusterQ: Semantic Feature Distribution Alignment for Data-Free Quantization," submitted to *TNNLS*, 2022.

* **Yangcheng Gao**, Zhao Zhang, "Fast Data-free Deep Neural Network Compression with Dictionary Pair Learning," submitted to *KAIS*, 2022.