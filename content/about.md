---
title: À propos
description: AlpesJUG est une association qui place au cœur de ses valeurs le partage, l'échange et la diffusion des savoirs techniques liés au développement logiciel. Cette initiative vise à réunir les professionnels, étudiants et enseignants de la région pour échanger autour des technologies et des avancées de la plateforme Java.
layout: page
---

# Organisateurs

<div class="authors xl:grid-cols-3">
  {#for id in cdi:authors.fields}
    {#let author=cdi:authors.get(id)}
    {#tln/authorCard
      firstName=author.firstName
      lastName=author.lastName
      avatar=author.avatar??
      profile=author.profile
    /}
  {/for}
</div>

# Résumé des informations officielles

- Dénomination : Alpes Java User Group (AlpesJUG)
- Numéro RNA : W732001424
- Date de parution au JOAFE : 4 décembre 2009
- Siège social : Barraux (38530), Isère
- Objet :  Réunir les professionnels, étudiants et enseignants de la région pour échanger autour des technologies et des avancées de la plateforme Java.

