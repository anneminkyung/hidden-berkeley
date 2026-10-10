---
layout: default
title: Welcome to Berkeley! Your Campus Guide
---

# Welcome to Berkeley! Your Campus Guide

Are you new to Berkeley and wondering where to start? This guide introduces some of the best places to study, explore, and enjoy your time on campus.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
