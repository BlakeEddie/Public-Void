---
title: About # will be overwritten by SEO.title below
date: 2020-08-05
layout: page
eleventyNavigation:
  key: main
  title: About # as it will appear in the nav
  order: 2 # order to display in the nav
seo:
  title: About Us # overrides 'title' above on both Page and META
  description:
  image:
---

{% columns "w-800" %}

  {% cols "bg-gray-100 rounded-lg pr-50" %}
    Bosco Bartilomo 
      {% pic "/assets/images/authors/bosco.jpg", "width:60%; border-radius:400px; margin-bottom: 1rem; margin-top: 1rem;" %}
      Bosco Bartilomo is the Director and Lead Designer of Public Void. After doing an undergraduate degree in software development, Bosco worked as a developer in industry before returning to do a Masters in User Experience Design. During this time he taught design at both the University of Queensland and RMIT, and during his studies achieved recognition internationally with his project Lumo as well as having his multi-modal project Jugaadogu exhibited in the NGV. He is now starting Public Void to pursue his passion of creating games, bringing a keen eye for user experience and production.
  {% endcols %}

  {% cols "bg-gray-100 rounded-lg pr-50" %}
    Harry Stitt 
    {% pic "/assets/images/authors/harry.jpg", "width:60%; border-radius:400px; margin-bottom: 1rem; margin-top: 1rem;" %}
    Harry Stitt is the Technical Director and Founder of Public Void. For Harry, making games is the perfect avenue for combining his various passions of art, music and software. Whilst working, he has spent most of his free time developing small games, entering game jams, and learning as much as he possible about game development. He is currently undertaking a PhD in mathematics, while working at Public Void.
  {% endcols %}

{% endcolumns %}
