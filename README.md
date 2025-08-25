---
title: career_conversation
app_file: app.py
sdk: gradio
sdk_version: 5.43.1
---

# README: Akhil Gunda's Agentic AI Personal Representative

## Introduction

Digital professional profiles are often static and impersonal, limiting genuine connections and failing to capture a candidate’s essence in conversations with potential employers. **Imagine an AI you can interact with—one that authentically represents your experience, skills, and ambitions.** This project is a pioneering example: it launches an agentic AI chatbot that acts as a dynamic, interactive proxy for Akhil Gunda, empowering future employers and collaborators to engage directly and meaningfully.

**This AI agent is live and available for public engagement via Hugging Face Spaces:**
👉 [Ask Akhil anything](https://huggingface.co/spaces/AkhilGunda16/career_conversation) — anyone can chat and interact with the agent now.

***

## Key Features

### Technologies Used

- **OpenAI LLM Integration:** Drives impactful, natural conversations.
- **Gradio:** Powers a robust and user-friendly chat interface, both locally and on Hugging Face.
- **pypdf \& Requests:** For personalized data ingestion (from resume/profile) and real-time notifications.
- **dotenv:** Secures configuration with easy environment variable management.


### Agentic AI Capabilities

- **Persona-Driven Responses:** The agent is built to answer as Akhil Gunda, using his real resume and background for context-rich, authentic replies.
- **Goal-Oriented Conversation:** It proactively steers interactions toward meaningful outcomes (e.g., collecting interested users’ contact info).
- **Tool Use:**
    - **Lead Capture:** Collects emails, names, and notes from users wanting to connect.
    - **Knowledge Gaps:** Logs all questions that the agent could not answer, providing feedback for further improvement.
    - **Push Notifications:** Akhil is notified instantly about important new leads or questions.
- **Context Awareness:** Leverages multi-turn conversation and personal documents (resume and summary) for nuanced, accurate information.
- **Autonomy:** Adapts strategies to optimize for engagement—hallmark of agentic AI.
- **Publicly Accessible Deployment:** Hosted on Hugging Face Spaces, making it easy for anyone, anywhere to ask Akhil anything in real time.

👉 **For a live demo, visit:** [https://huggingface.co/spaces/AkhilGunda16/career_conversation](https://huggingface.co/spaces/AkhilGunda16/career_conversation)

***

## Installation \& Running Locally

1. **Clone the repository:**

```bash
git clone https://github.com/akhilgunda/agentic-ai-representative.git
cd agentic-ai-representative
pip install -r requirements.txt
```

2. **Add your personal documents:**
Create a folder named `me` inside the main project directory and place your files inside it:
    - `Resume.pdf` — your resume or CV (PDF format)
    - `summary.txt` — a brief summary/about you in plain text
    - Optionally, add other files (e.g. `LinkedIn_Profile.pdf`, `Portfolio.pdf`, etc.)
3. **Set your identity:**
In `app.py`, change the line:

```python
self.name = "Your Full Name"
```

Replace with your own name.
4. **Configure environment variables:**
Create a `.env` file with your Pushover and OpenAI API keys:

```
PUSHOVER_TOKEN=your_pushover_token
PUSHOVER_USER=your_pushover_user_key
OPENAI_API_KEY=your_openai_api_key
```

5. **Run your agent locally:**

```bash
python app.py
```

The Gradio chat interface will launch; you can interact as your own AI representative, answering questions using your personal background, resume, and any other documents you have added.

***

## Hugging Face Spaces Deployment

**A major feature of this project is open deployment via Hugging Face Spaces.**
Hugging Face enables anyone to interact with Akhil's agent through a secure, scalable cloud-hosted Gradio interface, lowering the technical barrier for interviews, networking, and career conversations.

- **No setup required:** Visit [https://huggingface.co/spaces/AkhilGunda16/career_conversation](https://huggingface.co/spaces/AkhilGunda16/career_conversation) and start chatting instantly.
- **Broader impact:** Friends, employers, collaborators, and curious visitors worldwide can engage with Akhil’s digital persona—no local environment needed.

***

## Future Work

This agent presently represents Akhil Gunda, but its architecture is intended to pioneer **agentic personal AI for everyone**. Next steps include:

- **Generalization:** Making onboarding frictionless so anyone can easily deploy their own agent.
- **RAG (Retrieval-Augmented Generation):** Improving answer quality and depth by extending the agent’s memory and training using richer document bases (CVs, portfolios, recommendations, etc.).
- **Evaluator Agents:** Integrating agentic evaluators to continually review and suggest improvements to answers, thus increasing reliability and professionalism.
- **Multiple Personas:** Supporting career pivots, research profiles, and multi-domain personas for complex users.

***

## Conclusion

**Akhil Gunda’s Agentic AI Representative** is a first step towards a future where every professional can be present everywhere, all the time. By blending AI-driven context, real-time tool use, and autonomous conversation management, together with open cloud deployment via Hugging Face, it offers new opportunities for career growth and personal connection.

**Try it, share feedback, and imagine how this could reshape networking and hiring—starting today.**

👉 **Engage with Akhil’s agentic AI now:** [https://huggingface.co/spaces/AkhilGunda16/career_conversation](https://huggingface.co/spaces/AkhilGunda16/career_conversation)
<span style="display:none">[^2_1][^2_2]</span>

<div style="text-align: center">⁂</div>

[^2_1]: app.py

[^2_2]: https://huggingface.co/spaces/AkhilGunda16/career_conversation



