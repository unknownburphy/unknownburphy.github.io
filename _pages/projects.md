---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## MCP-based Financial Q&A System
**Nov 2024**
* Led idea development and overall project management
* Implemented logic for selecting and invoking appropriate tools based on user queries using MCP and ReAct prompting
* Built web demo using Streamlit
* **Tools Used:** MCP, Streamlit, LangChain, Python

## Emotional Support Model with Targeted Data Augmentation
**Oct 2024**
* Implemented pipeline for epoch-wise performance evaluation by topic and selective synthetic data augmentation
* Achieved comparable or superior performance using only 17% of synthetic data compared to full dataset usage

## Voice Lecture Summary Service
**July 2023 – Aug 2023**
* Developed a service that summarizes lecture videos and generates slide notes after splitting content
* Implemented web frontend and integrated with KT E2E STT technology
* Utilized GPT prompt engineering to generate summaries, titles, correct STT errors, and perform post-processing
* Created training data for fine-tuning KT Mi:dm (LLM) for summarization tasks
* **Tools Used:** React, langchain

## PDF Summary Service
**July 2023**
* Developed a web service that summarizes uploaded PDF documents after splitting them into appropriate chunks
* Deployed service using Vercel
* **Tools Used:** React, langchain, Vercel

## KakaoTalk Open Chat Summary Service (YOUM)
**Feb 2023**
* Developed a web service that summarizes KakaoTalk open chat conversations
* Researched and developed Dialogue Topic Segmentator (DTS) using unsupervised learning to address the lack of Korean datasets
* Built backend server with microservice architecture using FastAPI
* Implemented model packing and server using BentoML
* **Tools Used:** FastAPI, BentoML 