---
layout: page
title: About me
---

I am a medical student at University of Greifswald and working on my doctors's degree (Dr. med.) at the Department of Pharmacology and the Department of Neurosurgery.  I am running research on the malignant brain tumor glioblastoma multiforme, while following my interests in versatile topics like statistics and data science, openscience, reproducible research, ethics and philosophy.

<ul>
  {% if site.github_username %}
  <li>
    <a href="https://github.com/{{ site.github_username }}" class="icon fa-github">
      <span class="label">GitHub</span>
    </a>
  </li>
  {% endif %}

  {% if site.twitter_username %}
  <li>
    <a href="https://twitter.com/{{ site.twitter_username }}" class="icon fa-twitter">
      <span class="label">Twitter</span>
    </a>
  </li>
  {% endif %}

  {% if site.linkedin_username %}
  <li>
    <a href="https://linkedin.com/in/{{ site.linkedin_username }}" class="icon fa-linkedin">
      <span class="label">LinkedIn</span>
    </a>
  </li>
  {% endif %}

  {% if site.google_plus_username %}
  <li>
    <a href="https://plus.google.com/{{ site.google_plus_username }}" class="icon fa-google-plus">
      <span class="label">Google+</span>
    </a>
  </li>
  {% endif %}

  {% if site.facebook_username %}
  <li>
    <a href="https://www.facebook.com/{{ site.facebook_username }}" class="icon fa-facebook">
      <span class="label">Facebook</span>
    </a>
  </li>
  {% endif %}

  {% if site.dribbble_username %}
  <li>
    <a href="#" class="icon ai-researchgate">
      <span class="label">Dribbble</span>
    </a>
  </li>
  {% endif %}

  {% if site.researchgate_username %}
  <li>
    <a href="https://www.researchgate.net/profile/{{ site.researchgate_username }}" class="icon icon-ai ai-researchgate">
      <span class="label">Researchgate</span>
    </a>
  </li>
  {% endif %}

  {% if site.orcid_username %}
  <li>
    <a href="http://orcid.org/{{ site.orcid_username }}" class="icon icon-ai ai-orcid">
      <span class="label">ORCID</span>
    </a>
  </li>
  {% endif %}

  {% if site.email %}
  <li>
    <a href="mailto:{{ site.email }}" class="icon fa-envelope-o">
      <span class="label">Email</span>
    </a>
  </li>
  {% endif %}
</ul>
