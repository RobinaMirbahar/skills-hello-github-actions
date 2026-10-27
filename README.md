# Hello GitHub Actions

> **Author & Architect:** [Robina Mirbahar](https://github.com/RobinaMirbahar) (Google Developer Expert in Cloud & AI)  
> **Focus:** Event-Driven GitHub Actions Workflows, Custom Job Steps & Containerized Action Execution

---

## 🎯 Why I Built Hello GitHub Actions — CI/CD Automation Starter (Engineering Purpose & Real-World Value)

### 1. ⚙️ Mastering Event-Driven Repository Automation
I built this starter workflow repository to demonstrate how GitHub events (`push`, `pull_request`, `workflow_dispatch`) trigger containerized jobs and custom shell scripts automatically.

### 2. 🐳 Custom Docker Action Packaging
Includes a custom `Dockerfile` action and `entrypoint.sh` script showing how to package repeatable DevOps tasks into reusable workflow steps.

### 3. 📐 Clean Reference for CI/CD Onboarding
Provides a concise, readable reference for students and engineers learning GitHub Actions fundamentals.

---

## 🏗️ System Architecture

```mermaid
flowchart TD
    A["GitHub Repository Event (push / PR)"] --> B[".github/workflows/ Pipeline"]
    B --> C["Build Custom Docker Action Container"]
    C --> D["Execute entrypoint.sh Automation"]
    D --> E["Publish Job Summary & Status Check"]
```

---

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey RobinaMirbahar!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/RobinaMirbahar/skills-hello-github-actions/issues/1)

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)


---

### 🚀 Featured Google Cloud & Agentic AI Portfolio by Robina Mirbahar

| Repository | Architecture & Focus | Live Status |
| :--- | :--- | :--- |
| **[gemma4-multilora-adk-eval](https://github.com/RobinaMirbahar/gemma4-multilora-adk-eval)** | Dynamic Multi-LoRA Hot-Swapping & CI/CD Agent Evaluation (`adk eval`) on Cloud Run GPUs with Gemma 4 & vLLM | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/gemma4-multilora-adk-eval?style=flat-square&color=4285F4) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/gemma4-multilora-adk-eval?style=flat-square) |
| **[slothsre-napops](https://github.com/RobinaMirbahar/slothsre-napops)** | SlothSRE ("NapOps") — Overnight Gemma 4 & Google ADK Incident Digest Agent with OpenTelemetry & Sentry AI Monitoring | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/slothsre-napops?style=flat-square&color=34A853) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/slothsre-napops?style=flat-square) |
| **[streamforge-event-adk](https://github.com/RobinaMirbahar/streamforge-event-adk)** | Real-Time Event-Driven Multi-Agent Pipelines on Google Cloud with ADK (`ParallelAgent` & `LoopAgent`), Eventarc & Pub/Sub | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/streamforge-event-adk?style=flat-square&color=FBBC04) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/streamforge-event-adk?style=flat-square) |
| **[a2a-mcp-mesh-cloudrun](https://github.com/RobinaMirbahar/a2a-mcp-mesh-cloudrun)** | Agent-to-Agent (A2A) & Multi-MCP Mesh on Cloud Run with Gemma 4, Google ADK, Spanner Graph & AlloyDB | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/a2a-mcp-mesh-cloudrun?style=flat-square&color=EA4335) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/a2a-mcp-mesh-cloudrun?style=flat-square) |
| **[cloudguard-gemma-agent](https://github.com/RobinaMirbahar/cloudguard-gemma-agent)** | 6-Part Production Gemma Enterprise Agent Series (ADK, Cloud Run L4 GPU, Firestore, Model Armor, Vertex AI QLoRA) | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/cloudguard-gemma-agent?style=flat-square&color=4285F4) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/cloudguard-gemma-agent?style=flat-square) |
| **[Comic-Studio-Ai](https://github.com/RobinaMirbahar/Comic-Studio-Ai)** | Multi-Agent Comic Generator powered by Google Gemini API & FastAPI deployed on Google Cloud Run | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/Comic-Studio-Ai?style=flat-square&color=EA4335) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/Comic-Studio-Ai?style=flat-square) |
| **[vertex-ai-imagen3](https://github.com/RobinaMirbahar/vertex-ai-imagen3)** | Generate AI-powered product & editorial images using Google Vertex AI Imagen 3 in Google Colab | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/vertex-ai-imagen3?style=flat-square&color=34A853) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/vertex-ai-imagen3?style=flat-square) |
| **[Python-Learning-Assistant](https://github.com/RobinaMirbahar/Python-Learning-Assistant)** | AI-powered Python tutor covering 50+ interactive exercises with real-time feedback built with Streamlit + Gemini API | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/Python-Learning-Assistant?style=flat-square&color=FBBC04) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/Python-Learning-Assistant?style=flat-square) |
| **[cozy-ai-agent-cafe-game](https://github.com/RobinaMirbahar/cozy-ai-agent-cafe-game)** | Prompt Paws: 60 FPS Cozy AI Agent Bakery Simulation Game teaching RAG, Guardrails, Context Caching & Multi-Agent Loops | ![Stars](https://img.shields.io/github/stars/RobinaMirbahar/cozy-ai-agent-cafe-game?style=flat-square&color=7928CA) ![Last Commit](https://img.shields.io/github/last-commit/RobinaMirbahar/cozy-ai-agent-cafe-game?style=flat-square) |

<div align="center">
  <img src="https://raw.githubusercontent.com/RobinaMirbahar/RobinaMirbahar/main/ProfileImages/GithubBanner.svg" alt="Robina Mirbahar Banner" width="100%" />
</div>

<!-- AUTHOR_SIGNATURE_START -->
---

## 👩‍💻 About the Author

**Robina Mirbahar — Google Cloud & AI Architect**  
*Google Developer Expert (GDE) in Cloud & AI • Published Author • Multi-Agent Systems & Serverless GPU Builder*

[![GitHub](https://img.shields.io/badge/GitHub-RobinaMirbahar-181717?style=for-the-badge&logo=github)](https://github.com/RobinaMirbahar)
[![Medium](https://img.shields.io/badge/Medium-@robinamirbahar-000000?style=for-the-badge&logo=medium)](https://medium.com/@robinamirbahar)
[![DEV.to](https://img.shields.io/badge/DEV.to-robinamirbahar-0A0A0A?style=for-the-badge&logo=devdotto)](https://dev.to/robinamirbahar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Robina_Mirbahar-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/robina-mirbahar)
[![GDE Profile](https://img.shields.io/badge/Google_Developer_Expert-Profile-4285F4?style=for-the-badge&logo=google)](https://g.dev/RobinaMirbahar)
[![YouTube](https://img.shields.io/badge/YouTube-@RobinaMirbahar-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/@RobinaMirbahar)
[![X](https://img.shields.io/badge/X-@RobinaMirbahar-000000?style=for-the-badge&logo=x)](https://x.com/RobinaMirbahar)
[![Amazon Author](https://img.shields.io/badge/Amazon_Book-Cloud_Computing_Voyage-FF9900?style=for-the-badge&logo=amazon)](https://www.amazon.com/dp/B0D146249R)

<!-- AUTHOR_SIGNATURE_END -->
