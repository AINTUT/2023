---
layout: page
title: 最新消息
description: 課程最新訊息
---

# 最新消息

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
