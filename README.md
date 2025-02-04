# How to Build an AI Agent with CrewAI

This repository provides a step-by-step guide on **building an AI-powered content planner** using [CrewAI](https://github.com/crewAI/crewai) and [Groq's Llama 3](https://groq.com/) for inference.  

## ** Features**
- AI-powered **Content Planner**  
- Uses **CrewAI** to define AI Agents  
- Leverages **Groq’s Llama 3 (70B)** for fast inference  
- Generates **structured blog outlines**  

---

## ** Installation**

Run the following commands to install the required dependencies:  

```bash
!pip -qqq install pip --progress-bar off
!pip -qqq install 'crewai[tools]'==0.28.8 --progress-bar off
!pip -qqq install langchain-groq==0.1.3 --progress-bar off
