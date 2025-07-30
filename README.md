# TEDU LMS Assistant

## Overview

The **AI-Powered Academic Support Hub** is an innovative academic assistance platform designed specifically for TED University (TEDU) students. Leveraging advanced non-parametric large language model (LLM) grounding techniques—such as Retrieval-Augmented Generation (RAG), structured output control, and function calling—the system revolutionizes how students engage with their course materials and manage academic responsibilities.

This platform offers comprehensive study support, including the generation of practice questions, detailed explanations of study materials, and timely reminders to help students stay on track. By integrating directly with TEDU's Learning Management System (LMS) and utilizing robust databases, the system aims to enhance learning outcomes and student success.

---

## Key Features

- **Practice Question Generation**  
  Generates multiple-choice, open-ended, and true/false questions tailored to individual courses and study collections.

- **Interactive Study Assistance**  
  Provides explanations, Q&A sessions, and personalized study recommendations based on course materials.

- **Academic Reminder System**  
  Tracks deadlines, exams, and important milestones, sending proactive reminders to help students manage their schedules effectively.

---

## Functional Modules

### 1. Study Agent  
- Generates and validates practice questions.  
- Offers detailed explanations and interactive Q&A based on course syllabi.

### 2. Reminder Agent  
- Monitors academic calendar events and deadlines.  
- Sends timely reminders to students, aiding effective time management.

### 3. Chatbot Agent  
- Engages with students via chat to answer lecture-related questions.  
- Utilizes course materials as a knowledge base for accurate and relevant responses.

---

## Underlying Technologies & Grounding Techniques

- **Retrieval-Augmented Generation (RAG)**  
  Utilizes vector databases and semantic search to ground LLM outputs in verified course content, ensuring high accuracy.

- **Structured Output Control**  
  Maintains consistent system responses via JSON schema validation and predefined templates.

- **Multi-Agent Architecture**  
  Divides responsibilities among specialized agents for modularity, scalability, and efficient task handling.

- **Function Calling**  
  Provides precise control over agent operations with strict parameter validation and output enforcement.

---

## Data Integration

- Course syllabi and lecture materials  
- Deadlines, exam schedules, and milestone tracking  
- TEDU LMS integration  
- Persistent data stored in MySQL and Chroma vector databases

---

## Benefits

- Accurate and context-aware academic support powered by LLMs.  
- Consistent and reliable output formatting for seamless user experience.  
- Modular design promoting scalability and ease of maintenance.  
- Enhanced student engagement and improved learning outcomes.

---
