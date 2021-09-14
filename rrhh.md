---
layout: single
title: Recursos humanos
permalink: /rrhh/
toc: false
author_profile: true
classes: wide
sidebar:
    nav: "rrhh"
header:
    overlay_image: /assets/images/rrhh.jpg
    caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---

El ISISTAN posee investigadores de destacada trayectoria pertenecientes a las carreas del investigador CONICET o CICPBA y profesionales de la carrera del personal de apoyo del CONICET. Esas personas también son docentes en las carreras de informática de la UNCPBA. El ISISTAN posee también personal administrativo y becarios que realizan estudios de postgrado (doctorado y maestría).

<div style="font-size:0.8em">

<table id="table">
    <thead>
      <tr>
        <th>APELLIDO Y NOMBRE</th>
        <th>TÍTULO</th>
        <th>ROL</th>
        <th>CATEGORIA</th>
        <th>INSTITUCIÓN</th>
        <th>UNICEN</th>
        <th>SPU</th>
        <th>LINKS</th>
      </tr>
    </thead>
    <tbody>
    {% for member in site.data.personal %}
      <tr>
        <td><img src="{{ member.Avatar }}" alt="Foto" /> <a href="{{ member.Url }}">{{ member.Nombre }}</a></td>
        <td>{{ member.Titulo }}</td>
        <td>{{ member.Rol }}</td>
        <td>{{ member.Categoria }}</td>
        <td>{{ member.Institucion }}</td>
        <td>{{ member.Unicen }}</td>
        <td>{{ member.Spu }}</td>
        <td>
            {% if member.Pconicet %} <a href="{{ member.Pconicet }}"><i class="fas fa-university"></i></a> {% endif %}
            {% if member.Pscholar %} <a href="{{ member.Pscholar }}"><i class="fas fa-graduation-cap"></i></a> {% endif %}
            {% if member.Porcid %} <a href="{{ member.Porcid }}"><i class="fab fa-orcid"></i></a> {% endif %}
        </td>
      </tr>
    {% endfor %}
    </tbody>
</table>

</div>
