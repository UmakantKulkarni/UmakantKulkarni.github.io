---
layout: archive
title: "Publications"
permalink: publications/
author_profile: true
---

{% if site.author.googlescholar %}
<div class="wordwrap">
You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.  
</div>
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
<!--
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
-->

[Maestro: QoE-Aware Dynamic Resource Allocation in Wi-Fi Networks](https://doi.org/10.1145/3709371)  
**Umakant Kulkarni**, Khaled Diab, Lianjie Cao, Faraz Ahmed, Shivang Aggarwal, Puneet Sharma, Sonia Fahmy.  
Proceedings of the ACM on Networking, Volume 3, Issue CoNEXT1, Article 4, 24 pp., March 2025  

[Securing the Cloud-Native 5G Control Plane](https://ieeexplore.ieee.org/abstract/document/10774032)  
**Umakant Kulkarni**, Sonia Fahmy.  
In Proceedings of Workshop on Secure FutureG Wireless Communications and Networked Systems (Secure-FutureG),  
co-located with IEEE MILCOM, 6 pp., October 28, 2024.  

[Understanding the Impact of Wi-Fi Configuration on Volumetric Video Streaming Applications](https://dl.acm.org/doi/abs/10.1145/3609395.3610599)  
**Umakant Kulkarni**, Khaled Diab, Shivang Aggarwal, Lianjie Cao, Faraz Ahmed, Puneet Sharma, Sonia Fahmy.  
In Proceedings of ACM SIGCOMM Workshop on Emerging Multimedia Systems (EMS), 6 pp., September 2023.  

[Toward QoE-based Routing Path Selection](https://ieeexplore.ieee.org/abstract/document/10147938)  
**Umakant Kulkarni**, Yufeng Chen, Patrick Melampy, Sonia Fahmy.  
In Proceedings of the 2023 IEEE 24th International Conference on High Performance Switching and Routing (HPSR), pp. 114-119, June 2023.  

[Slicure5G: Secure Slicing for 5G (Poster)](https://www.cs.purdue.edu/homes/fahmy/posters/nsdi23poster5G.pdf)  
**Umakant Kulkarni**, Sonia Fahmy.  
USENIX NSDI, April 2023  

[Towards A Low-Cost Stateless 5G Core (Poster)](https://ieeexplore.ieee.org/abstract/document/9820393)  
**Umakant Kulkarni**, Amit Sheoran, Sonia Fahmy.  
IEEE LANMAN, 2 pp., July 2022.  

[The Cost of Stateless Network Functions in 5G](https://dl.acm.org/doi/abs/10.1145/3493425.3502749)  
**Umakant Kulkarni**, Amit Sheoran, Sonia Fahmy.  
In Proceedings of the ACM/IEEE Symposium on Architectures for Networking and Communications Systems 2021 (ANCS '21), pp. 73-79, December 2021.  