---
title: career_conversation
app_file: app.py
sdk: gradio
sdk_version: 5.43.1
---

# README: Akhil Gunda's Agentic AI Personal Representative

## Introduction

Modern job-seeking and networking are increasingly digital, yet most online profiles and resumes remain static, limiting genuine engagement and differentiation. Imagine if a potential employer or collaborator could interact with a dynamic **AI agent that truly represents you**—answering questions about your experience, skills, and background in real time, steering conversations towards meaningful interactions, and handling requests just as you would. This project is a step toward reshaping how professionals connect, present themselves, and create trust online.

**This repository launches an agentic AI powered chatbot that acts as a live, interactive proxy for Akhil Gunda.** It draws from Akhil's experiences, resume, and personal summary to provide authentic, intelligent responses to site visitors. This technology empowers individuals to put their best foot forward at scale, providing a unique edge in the job market and beyond.

***

## Project Structure and Features

### Key Technologies

- **OpenAI LLM Integration:** Handles natural, conversational interactions.
- **Gradio:** Provides an accessible and attractive web-based chat interface.
- **pypdf \& Requests:** Enable personalized data ingestion and outbound notifications.
- **dotenv:** Secure configuration through environment variables.


### Core Agentic AI Capabilities

This project showcases several **agentic AI** principles:

- **Persona-Driven Interaction:** The agent is strictly guided by Akhil's real biography, resume, and career summary, ensuring all responses feel authentic and personally relevant.
- **Tool Use:** The agent calls specialized functions to:
    - **Record leads:** Capture emails and user details from interested visitors.
    - **Log unknown queries:** Document what the agent can't answer, providing insights into visitor intent and knowledge gaps.
    - **Push notifications:** Alert Akhil instantly about important interactions.
- **Context Awareness:** The agent uses uploaded documents (resume, summary) and tracks ongoing conversation history for nuanced, knowledgeable replies.
- **Autonomous Conversation Flow:** Beyond simple question-answering, the agent steers conversations towards engagement (e.g., prompting users to share their email or propose collaboration). This is a hallmark of agentic AI, where the model pursues explicit goals with adaptive strategies.

***

## Installation \& Usage

1. Clone the repository:

```bash
git clone https://github.com/akhilgunda/agentic-ai-representative.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set up environment variables:
    - Create a `.env` file with your Pushover API credentials.
    - Place Akhil's `Resume.pdf` and `summary.txt` under the appropriate folder.
4. Launch the chat interface:

```bash
python app.py
```


***

## Future Work

While this release is tailored exclusively for Akhil Gunda, the broader vision includes making **agentic personal AI** available for everyone. Potential directions include:

- **Generalized Framework:** Architecting the codebase for easy onboarding of any user's resume and profile, enabling personal brand automation for all.
- **RAG Integration:** Employing Retrieval-Augmented Generation to boost the agent's depth and accuracy using richer document repositories or web data.
- **Evaluator Agents:** Building a separate "evaluator" agentic module that actively reviews, critiques, and suggests improvements to both the agent's answers and the underlying knowledge base, boosting response quality.
- **Domain Adaptation:** Supporting multiple personas (e.g., entrepreneur, researcher, developer), each with different knowledge sources and conversational styles.

***

## Conclusion

This project is an early demonstration of how **agentic AI can power highly personalized, interactive digital representations** for professionals. By blending advanced language models, tool-use capabilities, and goal-driven interaction, it paves the way for future-proof networking and recruiting experiences.

For now, it represents only Akhil Gunda, but its potential is universal: making AI-driven personal representation accessible, accurate, and actionable for everyone.

**Want to be represented by your own agent? Stay tuned and reach out! Collaborations and feedback are always welcome.**
<span style="display:none">[^1]</span>

<div style="text-align: center">⁂</div>

[^1]: app.py

