---
layout: page
title: Unseen Guardians
---

# The KazDemos Chronicles

**Héroes cotidianos. Trabajo invisible. Una empresa que evoluciona.**

**Everyday heroes. Invisible work. A company that evolves.**

KazDemos tiene cien personas y trece protagonistas. Seguimos sus decisiones, aprendizajes y desafíos mientras la empresa crece. Historias de manga sobre el trabajo cotidiano de TI, seguridad y gobierno de datos, con guías y ejercicios.

KazDemos has a hundred people and thirteen protagonists. We follow their decisions, learning and challenges as the company grows. Manga stories about everyday IT, security and data governance, with guides and learning exercises.

## Español

{% assign spanish_posts = site.posts | where: 'lang', 'es' %}
{% for post in spanish_posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% else %}
La primera aventura está en preparación.
{% endfor %}

## English

{% assign english_posts = site.posts | where: 'lang', 'en' %}
{% for post in english_posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% else %}
The first adventure is in preparation.
{% endfor %}

La empresa, los personajes y las situaciones son ficticios. The company, characters and events are fictional.

[Repositorio / Repository](https://github.com/ProfKaz/unseen-guardians)
