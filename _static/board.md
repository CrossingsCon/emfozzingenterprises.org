---
layout: page
title: Board of Directors
order: 40
---

{% for board_member in site.data.board %}
- **{{ board_member.name }}**, {{ board_member.title }}{% endfor %}
