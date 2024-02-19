---
layout: page
permalink: /software/
title: software
description: research software I have contributed to. If you use them in your work please cite the given references.
nav: false
nav_order: 7
---

<div class="post">
  <article>
      {% assign sorted_software = site.software | sort: "importance" %}
      {% for software in sorted_software %}
      {% assign remainder = forloop.index | modulo: 2 %}
        <hr>
        <div class="software float-{% if remainder == 1 %}left{% else %}right{% endif %}">
          {% if software.img %}
            {% assign software_image_path = software.img | prepend: 'assets/img/software_profiles/' %}
            {% assign software_image_class = 'img-fluid z-depth-1 rounded' %}
            {% capture sizes %}(min-width: {{site.max_width}}) {{ site.max_width | minus: 30 | times: 0.3}}px, (min-width: 576px) 30vw, 95vw{% endcapture %}
            {% include figure.liquid path = software_image_path class = software_image_class sizes = sizes alt = software.img zoomable=true %}
          {% endif %}
          <div class="links">
            {% if software.code %}
                <a href="{{software.code}}" class="btn btn-m z-depth-0" role="button">code</a>
            {% endif %}
            {% if software.cite %}
             <a class="abstract btn btn-sm z-depth-0" role="button">Cite</a>
            {% endif %}
          </div>

          {% if software.cite %}
            <!-- Hidden abstract block -->
            <div class="abstract hidden">
              <p>{% reference  software.cite  %}</p>
            </div>
          {% endif %}
        </div>

        <div class="clearfix">
          {% if software.title and software.description %}
            <h3>{{ software.title }} - {{ software.description }}</h3>
          {% endif %}
          {% if software.content %}
            {{ software.content }}
          {% endif %}
        </div>
      {% endfor %}
      <hr>

  </article>
</div>
