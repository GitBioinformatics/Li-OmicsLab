---
title: People
permalink: /people/
---

{% assign people_sorted = site.people | sort: 'joined' %}
{% assign role_array = "pi|postdoc|gradstudentdoctor|gradstudentmaster|researchstaff|visiting|others|alumni" | split: "|" %}

{% for role in role_array %}

{% assign people_in_role = people_sorted | where: 'position', role %}

<!-- Skip section if there's nobody -->
{% if people_in_role.size == 0 %}
  {% continue %}
{% endif %}

<div class="pos_header">
{% if role == 'postdoc' %}
<h1>Postdoctoral Fellows</h1>
 {% elsif role == 'pi' %}
<h1>Principal Investigator</h1>
 {% elsif role == 'gradstudentdoctor' %}
<h1>Graduate Students (Doctor)</h1>
 {% elsif role == 'gradstudentmaster' %}
<h1>Graduate Students (Master)</h1>
 {% elsif role == 'researchstaff' %}
<h1>Research Staff</h1>
 {% elsif role == 'visiting' %}
<h1>Visiting Scholars</h1>
 {% elsif role == 'others' %}
<h1>Honorary Members</h1>
 {% elsif role == 'alumni' %}
<h1>Alumni</h1>
{% endif %}
</div>


{% if role != 'alumni' %}
<div class="content list people">
  {% for profile in people_sorted %}
    {% if profile.position contains role %}
      <div class="list-item-people">
        <p class="list-post-title">
          <p class="name">{{ profile.name }}</p>
        </p>
      </div>    
    {% endif %}
  {% endfor %}
</div>
<hr>
{% else %}

<br>

| Who are they | When were they here           | Where they went |
| :----------- | :---------------------------- | :-------------- |
| ...          | Graduate student (0000-000)   | ...             |
| ...          | Graduate Student (0000- 0000) | ...             |
| ...          | Graduate Student (0000- 0000) | ...             |
| ...          | Postdoc (0000- 0000)          | ...             |

{% endif %}
{% endfor %}
