---
title: Lista de grupos para incursiones EX
---

<div class="container-fluid">
  <div class="row">
		{% for gym in site.gyms %}
    <div class="col">
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
