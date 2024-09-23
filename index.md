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

### [Task 1: Research Program Ideas](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_1_Research_Ideas.html)

Using Microsoft 365 Business Chat, research innovative educational programs or initiatives outside of TEALS. The goal is to find inspiration and explore successful elements that could inform the design of a new TEALS program. Consider emerging trends in technology education and literacy, as well as challenges faced by underserved 

### [Task 2: Draft a Program Proposal](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_2_Draft_a_Program_Proposal.html)

Based on your research, use Copilot in Word to draft a comprehensive proposal for your new TEALS initiative. The proposal should include the program’s objectives, target audience, expected outcomes, and key strategies for success.

### [Task 3: Create a Program Pitch Presentation](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_3_Create_a_Program_pitch_presentation.html)

Using the Word document created in Task 2, leverage Copilot in PowerPoint to develop a professional pitch deck. The presentation should be designed to communicate the vision, goals, and benefits of the proposed program to potential stakeholders or sponsors.

### [Optional Task 1: Generate Marketing Ideas](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Optional_Task_1_Create_an_image.html)

Use Microsoft 365 Copilot to quickly generate a range of creative outputs. It showcases the practical application of Copilot's features, emphasizing how you can extend your work in innovative ways.

### [Optional Task 2: Summarize a large document ](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Optional_Task_2_Data_mine_large_document.html)

Use Microsoft 365 Copilot in Word to efficiently extract and summarize key insights from large documents. It showcases Copilot's ability to streamline data mining, emphasizing its practical application in simplifying complex document analysis.

**Hyperlinks to each task are listed below.**

## Tasks

{% assign tasks = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}

| tasks |
| --- |
{% for activity in tasks %}| [{{ activity.task.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}