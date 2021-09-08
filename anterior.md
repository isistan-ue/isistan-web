---
layout: single
title: Personal anterior
permalink: /anterior/
toc: false
author_profile: true
classes: wide
sidebar:
    nav: "rrhh"
header:
    overlay_image: /assets/images/anterior.jpg
    caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---

Investigadores y becarios que trabajaron en el ISISTAN.

<div style="font-size:0.8em">

<table>
    <thead>
      <tr>
        <th>APELLIDO Y NOMBRE</th>
        <th>TÍTULO</th>
        <th>AÑO</th>
        <th>ACTIVIDAD ACTUAL</th>
        <th>EMPRESA</th>
      </tr>
    </thead>
    <tbody>
    {% for member in site.data.anteriores %}
      <tr>
        <td><img src="{{ member.Avatar }}" alt="Foto" /> <a href="{{ member.Url }}">{{ member.Nombre }}</a></td>
        <td>{{ member.Titulo }}</td>
        <td>{{ member.Fecha }}</td>
        <td>{{ member.Actividad }}</td>
        <td>{{ member.Empresa }}</td>
      </tr>
    {% endfor %}
    </tbody>
</table>

</div>

