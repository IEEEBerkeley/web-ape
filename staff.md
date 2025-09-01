---
layout: page
title: Staff
nav_exclude: false
description: A listing of all the course staff members.
---

# Staff

## Director

{% assign instructors = site.staffers | where: 'role', 'Director' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
