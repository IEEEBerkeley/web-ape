---
layout: page
title: Staff
nav_exclude: false
description: A listing of all the course staff members.
---

# Staff

## Director

{% assign directors = site.staffers | where: 'role', 'Director' %}
{% for staffer in directors %}
{{ staffer }}
{% endfor %}

## Software Lead

{% assign swleads = site.staffers | where: 'role', 'Software Lead' %}
{% for staffer in swleads %}
{{ staffer }}
{% endfor %}

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
