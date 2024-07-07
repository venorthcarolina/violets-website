---
title: Contact
nav:
  order: 5
  tooltip: Email and LinkedIn
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

As a recent graduate of the Institute for Advanced Analytics at North Carolina State University (NCSU) with an M.S. in Analytics, I am enthusiastic about applying my statistics and data science knowledge to explore organizations that leverage big data to tackle pressing challenges. I also have undergraduate experience in biostatistics, health equity, and research from UNC Chapel Hill. 

In my free time, you might find me running, exploring new cities, or trying out local restaurants with friends.

If you'd like to chat more, please feel free to contact me at my email or LinkedIn above. Let’s connect!

Detail-Oriented | Self-Starter | Experienced with Python, R, SQL, and Agile Methodologies

{%
  include button.html
  type="email"
  text="vwevans at alumni.unc.edu"
  link="vwevans@alumni.unc.edu"
%}

{%
  include button.html
  type= "LinkedIn"
  tooltip="My LinkedIn Profile"
  link="https://www.linkedin.com/in/violet-wen-evans/"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/team antares.jpg"
  caption="NCSU Practicum Team Blue 8"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/IMG_3917.jpg"
  caption="NCSU Summer Practicum Team"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
