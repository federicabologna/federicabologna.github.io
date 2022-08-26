---
layout: page
title: Contact me!
permalink: /contact/
---

<ul class="contact-list">
    {%- if site.email -%}<li><a href="mailto:{{ site.email }}">{{ site.email }}</a></li>{%- endif -%}
    {%- if site.twitter_username -%}<li><a href="https://www.twitter.com/{{ site.twitter_username| cgi_escape | escape }}">Twitter</a></li>{%- endif -%}          
    {%- if site.linkedin_username -%}<li><a href="https://www.linkedin.com/in/{{ site.linkedin_username| cgi_escape | escape }}">LinkedIn</a></li>{%- endif -%}
</ul>