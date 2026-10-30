---
date: Sat Jul 18 20:07:08 PDT 2026
last_modified_at: Thu Oct 29 23:35:42 PDT 2026
layout: single
title: "Master Page for Restricted Pages"
permalink: /sayunint-restricted-pages
categories:
tags:
toc: true
toc_label: "&nbsp;Table of Contents"
toc_icon: "fa-solid fa-list"
toc_sticky: true
usemathjax: true
author_profile: true
---

posted: {{ page.date| date: "%d-%b-%Y" }}
&amp;
updated: {{ page.last_modified_at| date: "%d-%b-%Y" }}
{: .notice--primary}

{% assign board_page = site.pages | where: "permalink", "/board-of-directors/" | first %}
{% assign bylaws = site.pages | where: "permalink", "/bylaws/ai-nexus" | first %}
{% assign bylaws_lean = site.pages | where: "permalink", "/bylaws/ai-nexus/lean" | first %}
{% assign board_policy = site.pages | where: "permalink", "/policies/board-expectations" | first %}

- [{{ bylaws.title }}]({{ bylaws.url }}){:target="_blank"}
- [{{ bylaws_lean.title }}]({{ bylaws_lean.url }}){:target="_blank"}
- [{{ board_policy.title }}]({{ board_policy.url }}){:target="_blank"}
- [{{ board_page.title }}]({{ board_page.url }}){:target="_blank"}
