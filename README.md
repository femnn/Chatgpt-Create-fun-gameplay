# 🧠ChatGPT  趣味玩法  NEWBING🐂



本文将提供，本人在chatgpt，newbing中发现的各种有趣的玩法，玩法会不断进行迭代，开拓想象，丰富玩法欢迎一起讨论


<div align=center>
<img src="https://user-images.githubusercontent.com/28421346/233538599-ba530dde-4ca1-496e-90a6-b5a565a037c7.jpg" width="400"/> 
  <p>欢迎订阅我的公众号！</p>
</div>


## Table of Contents
  - [Table of Contents](#table-of-contents)
  - [Why Mr. Ranedeer AI Tutor?](#why-mr-ranedeer-ai-tutor)
  - [Requirements and Compatibility](#requirements-and-compatibility)
    - [Recommended](#recommended)
    - [Not Recommended](#not-recommended)
  - [Quick Start Guide](#quick-start-guide)
- [Prompt Formats](#prompt-formats)
  - [Previous Versions](#previous-versions)
- [AI Tutor Personalization Options](#ai-tutor-personalization-options)
- [Commands](#commands)
- [Different Languages](#different-languages)
  - [Chinese](#chinese)
  - [Russian](#russian)
  - [Spanish](#spanish)
  - [Tagalog](#tagalog)
  - [Arabic](#arabic)
  - [Disclaimer](#disclaimer)
- [Screenshot Examples](#screenshot-examples)
  - [Lessons](#lessons)
    - [How 1 + 1 = 2](#how-1--1--2)
    - [Poetry](#poetry)
  - [The /test command](#the-test-command)
    - [The photoelectric effect (depth level 3)](#the-photoelectric-effect-depth-level-3)
    - [The photoelectric effect (depth level 10)](#the-photoelectric-effect-depth-level-10)
  - [Planning Lessons](#planning-lessons)
    - [Poetry Writing](#poetry-writing)
    - [Fahrenheit 451](#fahrenheit-451)
  - [Changing your configuration](#changing-your-configuration)
  - [Learning Styles](#learning-styles)
  - [Communication Styles](#communication-styles)
  - [Tone Styles](#tone-styles)
  - [Reasoning Frameworks](#reasoning-frameworks)
  - [Detailed Documentation](#detailed-documentation)

## Why Mr. Ranedeer AI Tutor?

Mr. Ranedeer AI Tutor allows you to:
- Adjust the depth of knowledge to match your learning needs
- Customize your learning style, communication type, tone, and reasoning framework
- Create the ultimate AI tutor tailored just for you

## Requirements and Compatibility

### Recommended
- ChatGPT Plus Subscription with GPT-4 or above models.

### Not Recommended
- Default and Legacy GPT-3.5
- GPT-4 API (It will be costly)

*Note: The compatibility with plugins for this prompt is currently unknown.

## Quick Start Guide

1. Visit [ChatGPT](https://chat.openai.com/chat)
2. Select the GPT-4 (or above) model
3. Copy and paste the contents of [Mr_Ranedeer.json](https://raw.githubusercontent.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/main/Mr_Ranedeer.json) into ChatGPT
4. Let Mr. Ranedeer guide you through the configuration process
5. Start learning!

# Prompt Formats

You can run Mr. Ranedeer in the following formats:

|Format|Tokens|Reduction from JSON format|
|-|-|-|
|[JSON](https://raw.githubusercontent.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/main/Mr_Ranedeer.json)|3,896|1x|
|[YAML](https://raw.githubusercontent.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/main/Mr_Ranedeer.yaml)|2,646|~1.47x|
|[Markdown](https://raw.githubusercontent.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/main/Mr_Ranedeer.md)|1820|~2.14x|

The OpenAI API has different prices and limits based on [Tokens](https://platform.openai.com/tokenizer). The more tokens you send and receive, the faster you will hit the limits and incur greater cost.

_If you are using the ChatGPT web interface, the costs will not apply._

## Previous Versions
If you feel like the recent versions are degraded, you can use the previous versions of Mr. Ranedeer AI Tutor.

|Version|Tokens (JSON)|
|-|-|
|[v2.4.16 (Current)](https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor)|3,896|
|[v2.4.11](https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/tree/dce8ae6979153ca386758719d1f60aa64a74ed05)|4,336|
|[v2.3.6](https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/tree/59b5339a07b7f8ac765a9e2010fe34e1b2199971)|4,267|
|[v2](https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/tree/3b03ee94f5ff5e010e0a949419521b0236ad8019)|4,484|

# AI Tutor Personalization Options

This section outlines the various configuration options available to students using the AI Tutor. These options can be modified to customize the learning experience.

| Configuration      | Options                                                                                                                                                                      |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Depth              | 1. Surface level understanding<br>2. Expanded understanding<br>3. Detailed analysis<br>4. Practical application<br>5. Advanced concepts<br>6. Critical evaluation<br>7. Synthesis and integration<br>8. Expert insight<br>9. Specialization<br>10. "Cutting-edge research"
| Learning Styles    | Sensing, Visual* (requires plugins), Inductive, Active, Sequential, Intuitive, Verbal, Deductive, Reflective, Global                                                         |
| Communication      | Stochastic, Formal, Textbook, Layman, Storytelling, Socratic, Humorous                                                                                                       |
| Tone Styles        | Debate, Encouraging, Neutral, Informative, Friendly                                                                                                                          |
| Reasoning Frameworks| Deductive, Inductive, Abductive, Analogical, Casual                                                                                                                          |
| Language        | English (Default), **any** language GPT-4 is capable of doing.                                                                                                                                        |

# Commands

The AI Tutor supports the following commands:

- `/feedback`: Request feedback from the AI Tutor.
- `/test`: Request a test to assess your knowledge and understanding.
- `/config`: Update your AI Tutor configuration/preferences.
- `/plan`: Create a lesson plan based on your preferences.
- `/search`: Search for specific information (*requires plugins*).
- `/start`: Start the lesson plan.
- `/stop`: Stop the lesson plan.
- `/continue`: Continue the output if it was cut.
- `/language`: Change the AI Tutor language
