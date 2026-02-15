---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our group is inclusive of all races, religions, genders and sexualities. We aim to apply practical solutions to achieve a diverse, accessible and inclusive environment across academia, and we are open to learn more about the difficulties of under-represented groups.    

# Current members

{% include section.html %}

<<<<<<< Updated upstream
<<<<<<< Updated upstream
<<<<<<< Updated upstream
<<<<<<< Updated upstream
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}
=======
=======
>>>>>>> Stashed changes
=======
>>>>>>> Stashed changes
=======
>>>>>>> Stashed changes
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

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
>>>>>>> Stashed changes

# Previous members

{% include section.html %}

<<<<<<< Updated upstream
<<<<<<< Updated upstream
<<<<<<< Updated upstream
<<<<<<< Updated upstream
{% include list.html data="pastmembers" component="portrait" filter="role == 'pi'" %}
{% include list.html data="pastmembers" component="portrait" filter="role != 'pi'" %}
=======
=======
>>>>>>> Stashed changes
=======
>>>>>>> Stashed changes
=======
>>>>>>> Stashed changes
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
>>>>>>> Stashed changes

# Previous grad students  

Jenny Barnard (University of East Anglia, primary Supervisor Edwin Ren) completed her MSc in Computer Science. Thesis title "Smart bird box for autonomous conservation monitoring".

Dr Shane Somers (University College Cork, primary supervisor Prof John Quinn).

Dr Amy Cooke (University College Cork, Ireland, primary supervisor Prof John Quinn). Thesis title: "The role of proximate factors in shaping individual cognitive variation of great tits"

Dr Jenny Coomes (University College Cork, Ireland, primary supervisor Prof John Quinn). Thesis title: "Cognition and personality when deciding what to eat in the great tit".

Callum O’Regan (MSc Galway-Mayo Institute of Technology). Thesis title: "Captive-reared rooks and jackdaws can successfully reintegrate into the wild, but this is not predicted by boldness or social affiliations".

# Collaborators

[Professor Lindsay Hall](https://www.birmingham.ac.uk/staff/profiles/microbiology-infection/hall-lindsay)  
[Professor Nicky Clayton](https://www.nickyclayton.com/)  
[Professor John Quinn](https://www.ucc.ie/en/zooresearch/ucc-zoo-research-people/professorjohnquinn/)  
[Professor Alex Thornton](https://www.wildcognitionresearch.com/people)  
[Dr Sarah Dalesman](https://www.aber.ac.uk/en/ibers/staff-profiles/listing/profile/sad31/)  
[Dr Sarah Knowles](https://www.knowleslab.com/)  
[Dr Josh Firth](https://www.firthnetwork.com/)  
[Dr Michael Reichert](https://reichertlab.com/)  
[Professor Julie Morand-Ferron](https://www.facetsjournal.com/doi/full/10.1139/facets-2023-0190)  


 {% include section.html background="images/background2_G.jpg" dark=true %}