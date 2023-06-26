---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
# Conference Paper
<ul>
<li>[Federated Intelligent Terminals Facilitate Stuttering Monitoring](https://sigport.org/documents/federated-intelligent-terminals-facilitate-stuttering-monitoring)
  
**Yongzi Yu**, Wanyong Qiu, Chen Quan, Kun Qian*, Zhihua Wang, Yu Ma, Bin Hu*, Björn W. Schuller, and Yoshiharu Yamamoto,in Proceedings of ICASSP, pp. 1-5, Rhodes Island, Greek, June 2023. (**CCF-B, oral**)
</li>
</ul>
# Jounal Paper

# Under review Paper

# Working Paper
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}




