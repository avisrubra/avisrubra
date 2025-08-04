---
layout: default
lang: es
title: Contacto
permalink: /es/contact/
---

{% include header.html %}

<h1 class="main-title">Contáctanos</h1>
<section class="transformation-section" style="justify-content:center;">
  <form method="POST" class="transformation-box" style="max-width:400px;">
    <label for="name">Nombre</label><br>
    <input type="text" id="name" name="name" required style="width:100%;padding:0.5rem;"><br><br>

    <label for="email">Correo electrónico</label><br>
    <input type="email" id="email" name="email" required style="width:100%;padding:0.5rem;"><br><br>

    <label for="message">Mensaje</label><br>
    <textarea id="message" name="message" rows="5" required style="width:100%;padding:0.5rem;"></textarea><br><br>

    <button type="submit" style="background:var(--red);color:white;border:none;padding:0.75rem 2rem;font-size:1rem;border-radius:8px;cursor:pointer;">Enviar</button>
  </form>
</section>
