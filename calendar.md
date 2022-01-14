---
layout: page
title: Lab Schedule
description: Listing of course modules and topics.
---

## Lab Information
All the lab Google Colab links will be shared here. Note that these will all be View Only, so to edit your own copy,
navigate to *File > Make a Copy* to make your own editable copy.

Labs 1 and 2 will be over Zoom, per Columbia policy in Spring 2022. The rest of the labs (3 onward) will be
in 516 Milstein Center, on Barnard's campus.

{% for module in site.modules %}
{{ module }}
{% endfor %}
