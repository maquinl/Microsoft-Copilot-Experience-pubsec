---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

## Description

In this interactive experience you will Design a new initiative for TEALS (Technology Education and Literacy in Schools) using Microsoft 365 Copilot to streamline research, proposal drafting, and presentation creation.

- You will have 25 minutes to complete the objective.
- In your browser, enter “Word.new” and then save a new document as “Copilot Research” to your OneDrive account.
- Try different Copilots, experiment with prompts to see what works best, and enjoy the creative process!

You will perform three tasks: 

### Task 1: Research Program Ideas

Using Microsoft 365 Business Chat, research innovative educational programs or initiatives outside of TEALS. The goal is to find inspiration and explore successful elements that could inform the design of a new TEALS program. Consider emerging trends in technology education and literacy, as well as challenges faced by underserved 

### Task 2: Draft a Program Proposal

Based on your research, use Copilot in Word to draft a comprehensive proposal for your new TEALS initiative. The proposal should include the program’s objectives, target audience, expected outcomes, and key strategies for success.

### Task 3: Create a Program Pitch Presentation

Using the Word document created in Task 2, leverage Copilot in PowerPoint to develop a professional pitch deck. The presentation should be designed to communicate the vision, goals, and benefits of the proposed program to potential stakeholders or sponsors.

**Hyperlinks to each task are listed below.**

## Taks

{% assign tasks = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}

| tasks |
| --- |
{% for activity in tasks %}| [{{ activity.task.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}