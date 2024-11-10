---
title: "010 Directing the Operation"
slug: "010-directing-the-operation"
permalink: "010-directing-the-operation.html"
layout: page
---

## Preview
You can have a look here
[preview]( 000-operation-management/010-directing-the-operation/preview/index.html )

## SCORM
You can download the SCORM package to be integrated into an LMS, e.g. Moodle.

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.slug and file.path contains  'zip' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}


## Content
The theoretical contents of the course are shown below.

{% assign files = site.static_files  %}

{% for file in files   %}
{% if file.path contains page.slug and file.path contains  'pdf' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}




