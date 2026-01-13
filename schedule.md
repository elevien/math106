---
title: Schedule
layout: page
bibliography:
- refs.bib
---

Unless otherwise noted all readings are from *Applied Stochastic Analysis* by E, Li and Vanden-Eijnden. Other textbooks are given on the <a href="{{ '/' | relative_url }}">home page</a>. Click the Week links for details on what we cover and suggestions on navigating the readings. **I will update these the Friday before we cover the material. Remember to refresh the webpage throughout the term!** 

The exercises listed on the Weekly pages should be completed by the Monday of the following week. They are not collected, but they are essential for exam preparation. It is strongly recommended that you attempt all exercises in the text related to the material we cover. I may add additional exercises while the material is being covered. If you cannot obtain a solution in a reasonable amount of time on your own, you may use ChatGPT for assistance or come to office hours. 

<table>
  <thead>
    <tr>
      <th>Day</th>
      <th>Date</th>
      <th>Topics</th>
      <th>Readings</th>
    </tr>
  </thead>
  <tbody>
  {% for w in site.data.schedule %}
    {% assign week_number = w.week | slice: 1, 1 %}
    <tr>
      <td><a href="{{ '/Week' | append: week_number | append: '/' | relative_url }}"><strong>{{ w.week }}</strong></a></td>
      <td></td><td></td><td></td>
    </tr>
    {% for m in w.meetings %}
    <tr>
      <td>{{ m.day }}</td>
      <td>{{ m.date }}</td>
      <td>{{ m.topics }}</td>
      <td>{{ m.readings }}</td>
    </tr>
    {% endfor %}
  {% endfor %}
  </tbody>
</table>