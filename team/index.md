---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our group is inclusive of all races, religions, genders and sexualities. We aim to apply practical solutions to achieve a diverse, accessible and inclusive environment across academia, and we are open to learn more about the difficulties of under-represented groups.    

# Current members

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" style="wide" %}

{% include section.html size="wide" %}

{% assign non_pi_members = site.members | where_exp: "item", "item.role != 'pi' and item.role != 'principal-investigator'" | sort: "name" %}
{% for member in non_pi_members %}
  {%
    include portrait.html
    name=member.name
    image=member.image
    role=member.role
    affiliation=member.affiliation
    links=member.links
    content=member.content
  %}
{% endfor %}

# Previous members

{% include list.html data="pastmembers" component="portrait" filter="role == 'principal-investigator'" %}

{% assign non_pi_pastmembers = site.pastmembers | where_exp: "item", "item.role != 'pi' and item.role != 'principal-investigator'" | sort: "name" %}
{% for member in non_pi_pastmembers %}
  {%
    include portrait.html
    name=member.name
    image=member.image
    role=member.role
    affiliation=member.affiliation
    links=member.links
    content=member.content
  %}
{% endfor %}

# Previous grad students  

Jenny Barnard (University of East Anglia, primary Supervisor Edwin Ren) completed her MSc in Computer Science. Thesis title "Smart bird box for autonomous conservation monitoring".

Dr Shane Somers (University College Cork, primary supervisor Prof John Quinn).

Dr Amy Cooke (University College Cork, Ireland, primary supervisor Prof John Quinn). Thesis title: "The role of proximate factors in shaping individual cognitive variation of great tits"

Dr Jenny Coomes (University College Cork, Ireland, primary supervisor Prof John Quinn). Thesis title: "Cognition and personality when deciding what to eat in the great tit".

Callum O’Regan (MSc Galway-Mayo Institute of Technology). Thesis title: "Captive-reared rooks and jackdaws can successfully reintegrate into the wild, but this is not predicted by boldness or social affiliations".

# Collaborators

<div class="center">
  <a href="https://www.birmingham.ac.uk/staff/profiles/microbiology-infection/hall-lindsay">Professor Lindsay Hall</a><br>
  <a href="https://www.nickyclayton.com/">Professor Nicky Clayton</a><br>
  <a href="https://www.ucc.ie/en/zooresearch/ucc-zoo-research-people/professorjohnquinn/">Professor John Quinn</a><br>
  <a href="https://www.wildcognitionresearch.com/people">Professor Alex Thornton</a><br>
  <a href="https://www.aber.ac.uk/en/ibers/staff-profiles/listing/profile/sad31/">Dr Sarah Dalesman</a><br>
  <a href="https://www.knowleslab.com/">Dr Sarah Knowles</a><br>
  <a href="https://www.firthnetwork.com/">Dr Josh Firth</a><br>
  <a href="https://reichertlab.com/">Dr Michael Reichert</a><br>
  <a href="https://www.facetsjournal.com/doi/full/10.1139/facets-2023-0190">Professor Julie Morand-Ferron</a>
</div>


 {% include section.html background="images/background2_G.jpg" dark=true %}