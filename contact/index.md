---
title: Contact
nav:
  order: 5
  tooltip: Email and LinkedIn
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="vwevans at alumni.unc.edu"
  link="vwevans at alumni.unc.edu"
%}
{%
  include button.html
  type="phone"
  text="(919)896-1316"
  link="+1-919-896-1316"
%}
{%
  include button.html
  type="LinkedIn"
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
  image="images/photo.jpg"
  caption="Lorem ipsum"
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
