---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you’re interested in our work or have any questions, feel free to get in touch.
We welcome collaboration, student inquiries, and general questions about the lab.
You can reach us by email or visit us in person at the University of Missouri, Naka Hall, 3rd floor, Room 349C.

{%
  include button.html
  type="email"
  text="bunyak@missouri.edu"
  link="bunyak@missouri.edu"
%}
{%
  include button.html
  type="phone"
  text="573-882-6483"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/shRbZWiCxzukfjhJ7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/mizzou1.jpg"
  caption="University of Missouri"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/naka_hall.jpg"
  caption="Naka Hall"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% capture col2 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% capture col3 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
