---
title: Lista de grupos para incursiones EX
---

<div class="container-fluid">
<p>Estos grupos son para poder organizarse mejor en las incursiones EX, por tanto pedimos entrar solo en los grupos para los que tengas pase EX, una vez dentro hablar sobre la organización de la incursión (segundas rondas, retrasos, etc) y al acabar la incursión (no antes) salir de los mismos.</p>
<p>Al entrar al grupo deberías encontrar una raid en el mensaje anclado para apuntarte. Si no es así envía una captura de pantalla del pase ex al grupo para crearla.</p>
<p>Si sabes de antemano que vas a tener algún problema llegar a tiempo a la incursión avisa cuanto antes para intentar buscar una solución lo antes posible, no esperes a última hora porque será más difícil.</p>
  <div class="row">
	{% assign sorted = (site.gyms | sort: 'name') %}
	{% for gym in sorted %}
    <div class="col-6 col-sm-6 col-md-4 col-lg-3">
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
