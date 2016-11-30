---
layout: default
---

# Some html emails for LAXART:

## Most recent "Save the Date" Email:

{% for dates in site.categories.dates limit:2 %}
[{{dates.title}}]({{site.baseurl}}{{dates.url}})
{% endfor %}


## Most recent "Press Release" Email:

{% for press in site.categories.press limit:2 %}
[{{press.title}}]({{site.baseurl}}{{press.url}})
{% endfor %}