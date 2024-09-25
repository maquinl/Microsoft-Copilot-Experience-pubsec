---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

## Description

In this interactive experience you will come up with a new giving Campaign using Microsoft 365 Copilot to streamline research, proposal drafting, and presentation creation.

- You will have 25 minutes to complete the objective.
- In your browser, enter “Word.new” and then save a new document as “Copilot Research” to your OneDrive account.
- Try different Copilots, experiment with prompts to see what works best, and enjoy the creative process!

You will perform three tasks: 

### [Task 1: Research Program Ideas](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_1_Research_Ideas.html)

Using Business Chat in the Microsoft 365 App (Microsoft.com/Copilot), research giving campaign ideas and philanthropic initiatives that align with corporate social responsibility goals. Focus on identifying successful strategies and emerging trends, with the goal of brainstorming and developing at least one new giving campaign idea inspired by your findings. This task is about generating an idea to build on in the next steps.

### [Task 2: Draft a Program Proposal](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_2_Draft_a_Program_Proposal.html)

Based on your research using BizChat, use Copilot in Word to draft a comprehensive proposal for your new giving campaign idea. The proposal should include a summary of the campaign’s objective, a detailed breakdown of expected outcomes, key strategies for success, and potential challenges.

### [Task 3: Create a Program Pitch Presentation](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_3_Create_a_Program_pitch_presentation.html)

Using the Word document created in Task 2, leverage Copilot in PowerPoint to develop a pitch deck for your campaign idea. The presentation should be designed to communicate the vision, goals, and benefits of the proposed giving campaign to potential stakeholders or sponsors.

### [Task 4: Collaborate Using Pages](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_4_Collaborate_Using_Pages.html)

Experience the new “Pages” functionality, which allows you to collaborate and organize ideas in a dynamic, shareable space. 

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