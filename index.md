---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Content Directory


## Course Description

Explore the transformative potential of Microsoft Copilot and its impact on organizational efficiency. Designed for executives and business leaders without a Copilot license, this experience delves into the art of crafting effective prompts, offers an interactive experience, and demonstrates how Microsoft Copilot for Microsoft 365 can seamlessly integrate into daily business workflows to boost productivity and innovation.

The primary objectives for this delivery is to:

- Teach how to craft effective prompts
- Demonstrate Microsoft Copilot (web scope) and guide participants through an interactive experience
- Demonstrate Microsoft Copilot for Microsoft 365 - Microsoft Copilot (work scope), word, Outlook, and teams
- Invite participants to download and try Microsoft Copilot for Mobile

Hyperlinks to each of the demos are listed below.

## Taks

{% assign tasks = site.pages | where_exp: "page", "page.url contains '/Instructions/Labs'" %}

| Task |
| --- |
{% for activity in tasks %}
| [{{ activity.task.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
