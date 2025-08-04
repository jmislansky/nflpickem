---
layout: week
title: "Week 1"
permalink: /week_1
---
WIP

<!--
<img src="images/color_logos/{{ site.arizona_logo }}">
-->

<table>
  {% for row in site.data.2025-26.week_1 %}
    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>

<style>
tr td:first-child  {
  background-color: maroon;
  color: white;
}

table {
  text-align:center;
  Table-layout: fixed;
  Width: 300%;
} 

</style>

