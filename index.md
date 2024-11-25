---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

## Proof of concept - Microsoft 365 Copilot Immersion Experience: Pub Sec

Insert summary of activity

You will perform four tasks: 

### [Task 1: Research Campaign Ideas](https://maquinl.github.io/Microsoft-Copilot-Experience-pubsec/Instructions/Labs/Task_1_Research_Ideas.html)

### [Task 2: TBD]

### [Task 3: TBD]

### [Task 4: TBD]

Based on your research, use Copilot in Word to draft a comprehensive proposal for your new TEALS initiative. The proposal should include the program’s objectives, target audience, expected outcomes, and key strategies for success.

### [Task 3: Create a Program Pitch Presentation](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_3_Create_a_Program_pitch_presentation.html)

Using the Word document created in Task 2, leverage Copilot in PowerPoint to develop a professional pitch deck. The presentation should be designed to communicate the vision, goals, and benefits of the proposed program to potential stakeholders or sponsors.

### [Task 4: Collaborate Using Pages](https://maquinl.github.io/CELA-Academy-Microsoft-Copilot-Experience/Instructions/Labs/Task_4_Collaborate_Using_Pages.html)

Experience the new “Pages” functionality, which allows you to collaborate and organize ideas in a dynamic, shareable space. Pages act much like Loop components, making it easy to capture and refine content directly within your chat.

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


