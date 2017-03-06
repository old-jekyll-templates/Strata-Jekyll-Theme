---
layout: page
title: About me
---
<span class="image right"><img src="{{ site.url }}/images/avatar_big.jpg"></span>

I am a medical student at University of Greifswald and working on my doctor's degree (Dr. med.) at the Department of Pharmacology and the Department of Neurosurgery. Furthermore I am a graduate student in Health Care Management at the University of Greifswald. I am holding a B. Sc. in Biomedical Science from the University Medicine Greifswald. On my working days I am running research on the malignant brain tumor glioblastoma multiforme, while following my interests in versatile topics like statistics and data science, openscience, reproducible research, ethics and philosophy. When there is time to unbend, I like to go sailing, driving motorcycle or doing sports.

Feel free to contact me on any channel:
<ul>
  {% if site.github_username %}
  <li>
    <a href="https://github.com/{{ site.github_username }}" class="icon fa-github">
      Github<span class="label">GitHub</span>
    </a>
  </li>
  {% endif %}

  {% if site.twitter_username %}
  <li>
    <a href="https://twitter.com/{{ site.twitter_username }}" class="icon fa-twitter">
      Twitter<span class="label">Twitter</span>
    </a>
  </li>
  {% endif %}

  {% if site.linkedin_username %}
  <li>
    <a href="https://linkedin.com/in/{{ site.linkedin_username }}" class="icon fa-linkedin">
      LinkedIn<span class="label">LinkedIn</span>
    </a>
  </li>
  {% endif %}

  {% if site.google_plus_username %}
  <li>
    <a href="https://plus.google.com/{{ site.google_plus_username }}" class="icon fa-google-plus">
      Google+<span class="label">Google+</span>
    </a>
  </li>
  {% endif %}

  {% if site.facebook_username %}
  <li>
    <a href="https://www.facebook.com/{{ site.facebook_username }}" class="icon fa-facebook">
      Facebook<span class="label">Facebook</span>
    </a>
  </li>
  {% endif %}

  {% if site.researchgate_username %}
  <li>
    <a href="https://www.researchgate.net/profile/{{ site.researchgate_username }}" class="icon icon-ai ai-researchgate">
      Researchgate<span class="label">Researchgate</span>
    </a>
  </li>
  {% endif %}

  {% if site.orcid_username %}
  <li>
    <a href="http://orcid.org/{{ site.orcid_username }}" class="icon icon-ai ai-orcid">
      ORCID<span class="label">ORCID</span>
    </a>
  </li>
  {% endif %}

  {% if site.email %}
  <li>
    <a href="mailto:{{ site.email }}" class="icon fa-envelope-o">
      Email<span class="label">Email</span>
    </a>
  </li>
  {% endif %}
</ul>
