---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We’re a group of researchers, students, and collaborators working together on problems in computer vision, AI, and image analysis. Everyone brings their own skills and interests, and we learn a lot from each other along the way. Get to know the people behind the projects!

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

We believe good research comes from good collaboration. Our team brings together different backgrounds and skills, and that diversity is what drives our work forward.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/lab_members/team/6.jpg" %}
{% include figure.html image="images/lab_members/team/2.jpg" %}
{% include figure.html image="images/lab_members/team/3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
