---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
1. 
**Y.X.Sun**, C.Schroeder. Effective time step restrictions for explicit MPM simulation. In ACM Symposium on Computer Animation. *SCA' 20*.
1. 
G.K.Zhang, Y.Luo, D.D.Zhu, Y.X.Xu, **Y.X.Sun**, J.W.Lu. Spatial Pyramid Dilated Network for Pulmonary
Nodule Malignancy Classication. In Proceedings of International Conference on Pattern
Recognition. *ICPR'18*. *Accepted*. 
1. 
J.U.Davis, J.Gong, **Y.X.Sun**, P.K.Chilana, X.D.Yang. CircuitStyle: A System for Peripherally Reinforcing Best Practices in Hardware Computing. In ACM Symposium on User Interface Software and
Technolog. *UIST'19*. *Accepted*.  



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
