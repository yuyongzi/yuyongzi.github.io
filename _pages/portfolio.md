---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}
# Federated Intelligent Terminals Facilitate Stuttering Monitoring
<center>
<img src="/images/FITs.png">
</center>

Stuttering is a complicated language disorder. The most common form of stuttering is developmental stuttering, which begins in childhood. Early monitoring and intervention are essential for the treatment of children with stuttering. Automatic speech recognition technology has shown its great potential for non-fluent disorder identification, whereas the previous work has not considered the privacy of users' data. To this end, we propose federated intelligent terminals for automatic monitoring of stuttering speech in different contexts. Experimental results demonstrate that the proposed federated intelligent terminals model can analyze symptoms of stammering speech by taking personal privacy protection into account. Furthermore, the study has explored that the Shapley value approach in the federated learning setting has comparable performance to data-centralised learning.

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

