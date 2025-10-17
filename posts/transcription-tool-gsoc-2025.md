---
title: GSoC 2025 Journey – Transcription Tool for Usability Testing  
date: 2025-10-17  
author: Basma Elhoseny  
gravatar: 3ab2b1c88f3b4a1f04f9c7be7e1f9e9c
linkedin: 'https://www.linkedin.com/in/basmaelhoseny01/'  
github: 'basmaelhoseny01'  
---

Over the summer, I had the opportunity to join **Google Summer of Code 2025** with **RUXAILAB**, working on a project that brings artificial intelligence and usability research closer together. My project — the **Transcription Tool for Usability Testing** — focuses on making user research faster, smarter, and more collaborative.

---

## The Problem

In traditional usability testing, moderators record user sessions to analyze how participants interact with digital products. But when these recordings last for hours, revisiting specific moments becomes time-consuming and inefficient. Researchers often spend more time locating the right clips than understanding user behavior.

## The Solution

The **Transcription Tool** solves this by automatically generating **task-based transcriptions** that segment usability sessions according to user activities. Instead of scrolling through entire videos, researchers can quickly jump to the exact moment where a user struggled with a button, misunderstood a form, or completed a task successfully.

The tool integrates AI models to:
- Transcribe and segment recordings into meaningful task blocks  
- Label each segment by the task name and participant role  
- Allow quick review, annotation, and export of transcripts  

This approach turns hours of raw recordings into searchable, structured, and shareable insights — making usability evaluation more efficient and transparent.

---

## How It Works

The system is powered by **FastAPI** on the backend, integrated with **OpenAI’s Whisper model** for speech-to-text. It supports **GPU-accelerated deployment on Google Cloud Run**, making it scalable for real-world usability labs.

1. Researchers upload their session recordings  
2. The API performs automatic transcription and segmentation  
3. Each task and speaker is detected, labeled, and stored for later access  
4. Transcripts can be reviewed and exported for collaborative analysis  

Everything is open source and designed for integration with future RUXAILAB tools.

---

## Key Features

- **Automatic Transcription**: Converts usability session recordings into clean text  
- **Task-Based Segmentation**: Splits transcripts according to moderator-defined tasks  
- **Speaker Separation**: Distinguishes between moderator and participant speech  
- **Annotation & Export**: Researchers can mark key quotes and export relevant clips  
- **Cloud Deployment**: Optimized for GPU or CPU execution via Google Cloud Run  

---

## Impact

This tool empowers usability researchers, designers, and students to:
- Save hours of manual transcription work  
- Focus on analysis rather than logistics  
- Collaborate more effectively in remote research contexts  

As I mentioned during development:  
> “I wanted to create something that makes user research more efficient and open for everyone. Being part of Google Summer of Code has shown me how collaboration and open source can truly make a difference.”

---

## Behind the Scenes

The project was developed in close collaboration with my mentors from **RUXAILAB**, who guided me through architectural decisions, AI integration, and usability principles.  
Technically, it combines:
- **Python + FastAPI** backend  
- **Dockerized Cloud Deployment** (Artifact Registry + Cloud Build + Cloud Run)  
- **OpenAI Whisper API** for multilingual speech recognition  
- **Task-level schemas and data validation** via Pydantic  
- **Scalable architecture** ready for multi-user expansion  

---

## About Me

I’m **Basma Elhoseny**, a Computer Engineer from **Cairo University** (Faculty of Engineering, Computer Section, Class of 2024) currently pursuing my MSc in **Artifical Intelligence**. I’m passionate about AI-driven usability, developer tools, and accessible design.

---

## About RUXAILAB

**RUXAILAB (Remote Usability eXperiments & Artificial Intelligence Lab)** is an open-source research initiative focused on improving usability, accessibility, and UX evaluation through AI and remote testing. Founded by **Dr. Marc González** in Spain, the lab collaborates with researchers and developers worldwide to make digital systems more inclusive and human-centered.

> “Basma’s work represents the essence of what GSoC stands for — combining technical excellence, creativity, and collaboration for global impact,”  
> — *Dr. Marc González, Founder of RUXAILAB*

---

## About Google Summer of Code (GSoC)

**Google Summer of Code** is a global program that connects new contributors with open-source organizations. Over 12 weeks, participants collaborate with mentors to build software that benefits the community. The program encourages innovation, learning, and diversity — helping young developers like me grow through real-world impact.

---

## Links

- **Repository:** [https://github.com/ruxailab/transcription-api](https://github.com/ruxailab/transcription-api)  
- **Organization:** [https://ruxailab.web.app](https://ruxailab.web.app)
- **GSoC Project:** [https://summerofcode.withgoogle.com/programs/2025/projects/aOHlFhUA](https://summerofcode.withgoogle.com/programs/2025/projects/aOHlFhUA)

---

This project marks just the beginning — the next step will focus on integrating sentiment analysis, participant emotion detection, and usability metrics visualization.  

Thanks to the **RUXAILAB mentors**, the **open-source community**, and **Google Summer of Code** for making this journey possible.
