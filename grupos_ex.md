---
title: Lista de grupos para incursiones EX
---

<div class="container-fluid">
  <div class="row">
		{% for gym in site.gyms %}
    <div class="col-xs-6 col-sm-6 col-md-4 col-lg-3">
      <a href="{{gym.group}}">
        <img src="{{gym.image}}" class="rounded-circle mx-auto d-block">
        <div class="text-center">
          {{gym.name}}
        </div>
      </a>
    </div>
    {% endfor %}
  </div>
</div>
