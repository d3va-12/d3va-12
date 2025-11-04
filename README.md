# Hi, I'm Devendra 👋

![wave](https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif)

**Career-focused developer • Data enthusiast • AI tinkerer**

I build practical AI tools, career-guidance products and interactive web apps. I turn startup ideas into working projects — one of those is **Destiny Dive**, my personal project that began as a startup concept.

<div align="center">
  <a href="mailto:devendra99651@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/d3va-12">
    <img src="https://komarev.com/ghpvc/?username=d3va-12&label=PROFILE+VIEWS&style=for-the-badge&color=blueviolet" alt="Profile Views"/>
  </a>
</div>

---

<!-- Replaced the previous section-banner with a clean animated header banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rounded&color=gradient&height=120&section=header&text=Devendra+Kumar&fontSize=50&animation=fadeIn" alt="Devendra Kumar Banner" />
  <br/>
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=2500&pause=700&color=00F7FF&width=680&lines=AI+Engineer+•+Full+Stack+Developer;Building+Career+Guidance+Platforms;Creating+AI+Tools+That+Empower+Learners" alt="typing"/>
</div>

---

## 🚀 What I build
- 🤖 **AI-powered assistants & chatbots** — concise, practical conversational agents tuned for students and workflows.  
- 🎓 **Career-guidance systems & decision flows** — interactive flows that map students to courses, colleges and career roadmaps.  
- 🧠 **ML media tools** — frame interpolation, enhancement and temporal stabilization for video & animation.  
- 📊 **Data dashboards & analytics** — Power BI + Python for actionable visual storytelling.  
- 🌐 **Full-stack web apps** — React frontend + Node/Express APIs + MongoDB/MySQL.

---

## 🧩 Featured — Destiny Dive
**Destiny Dive** — an interactive career-guidance platform (personal project).

**Core capabilities**
- 🎯 **Dynamic Career Flow Engine** — adaptive question trees that personalise recommendations for Indian and foreign university paths.  
- 🧭 **Integrated Mistral 7B Chatbot** — conversational advice embedded in flows; context-aware suggestions based on profile data.  
- 🧱 **Gamified Profiles** — XP, badges, daily quests, and mentor suggestions to motivate students.  
- 🧩 **Career Roadmap Generator** — produces semester-by-semester study plans, skill milestones and recommended internships.

**Architecture**
- Frontend: React + Tailwind (SPA)  
- Backend: Node.js + Express (REST + WebSocket)  
- Data: MongoDB (profiles, quests), MySQL (analytics)  
- AI: Mistral 7B (local inference), prompt templates, safety filters

---

## 🧠 Projects

---

### 1️⃣ Frame Interpolation Engine ![frames]
(https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaWx5dWVkeDloa3ZiOGc1czNmdjNiOTBodGVuNnR6MDdmdm81bjM2diZlcD12MV9naWZzX3NlYXJjaCZjdD1n/xTiJ4cVWew0klLuY96/giphy.gif)
**Overview:** Research-quality engine that synthesizes intermediate frames for smoother playback and slow-motion effects.

**Key features**
- Multi-frame synthesis to reduce flicker & temporal artifacts.  
- Motion-aware warping with explicit occlusion handling.  
- Batch CLI + web preview UI, FFmpeg pipeline for encoding.  
- GPU-accelerated inference (CUDA / TensorRT) for near-real-time operation.

**Architecture & Tech**
- Core: PyTorch models (optical flow + synthesis network)  
- Pre/post: OpenCV, FFmpeg for encoding and stitching  
- Acceleration: CUDA, optional TensorRT conversion  
- UI: React preview with upload/batch controls

**Example usage**
- Slow-motion conversion for 24→60 fps, animation smoothing, frame rate upscaling for legacy footage.  
**Status:** Production prototype, editable parameters for motion-blend, occlusion threshold.

---

### 2️⃣ Mistral 7B Chatbot (Career Guidance) ![chatbot]
(https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbHFlM2J1dWdobmg1enNjd3NvbDFxbXp4YnlwaHk4bDFlZ2I1M3B3MSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/S60CrN9iMxFlyp7uM8/giphy.gif)
**Overview:** Local deployment of Mistral-7B-Instruct (quantized) tuned for concise, student-friendly career guidance.

**Key features**
- Contextual replies using user profile & recent activity.  
- Personality & tone presets (concise, mentor-like, friendly).  
- Offline voice pipeline: Whisper (STT) + TTS for spoken interactions.  
- Safety & fallback logic to avoid unreliable recommendations.

**Architecture & Tech**
- Model: Mistral 7B (GGUF / quantized), run on local GPU / ONNX runtime where applicable  
- API: Flask / FastAPI for model serving; Node/Express gateway for web clients  
- Realtime: Socket.IO for chat streaming and typing indicators  
- Integrations: Destiny Dive profile connectors for personalised suggestions

**Example usage**
- “Which campuses in Bangalore offer CS with strong placements?” → chatbot replies with ranked list and suggested next steps (sample prep resources).

---

### 3️⃣ AI-Powered Mind Map Generator ![mindmap]
(https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZjQ3Z2p1ZTV2b2hvYnh6cGt0cDBmdXVncTJ6bmNid3JyNDNsYmR4ZSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/h7uQzyT755jVibc0fj/giphy.gif)
**Overview:** Converts natural language prompts into interactive, exportable mind maps for study planning and brainstorming.

**Key features**
- Automatic topic extraction → hierarchical graph generation.  
- Auto layout & clustering with D3.js; nodes are draggable and editable.  
- Export to SVG/PNG/JSON; shareable templates for study sessions.  
- Color themes, node icons and priority markers.

**Architecture & Tech**
- NLP: LLM prompt pipeline to extract entities & relations  
- Graph: NetworkX / custom heuristics for hierarchy building  
- Rendering: D3.js + React, SVG export utilities  
- API: FastAPI to accept prompts and return JSON graph

**Example usage**
- Input: “Prepare for Data Structures semester” → Generates subject branches, topic checklist, estimated study hours per topic.

---

### 4️⃣ PromptGen — Prompt Engineering Toolkit ![prompt]
(https://media.giphy.com/media/26gslkq3G1Qx3dG4g/giphy.gif)
**Overview:** Prompt versioning & testing environment to iterate quickly on LLM prompts across tasks.

**Key features**
- Template library: classification, summarization, QA, conversation.  
- A/B testing: run multiple prompt variants and compare outputs.  
- Metrics & scoring: BLEU/ROUGE + embedding similarity + human labels.  
- Prompt history + tagging for reproducibility.

**Architecture & Tech**
- Backend: Node.js + Python evaluation scripts  
- Storage: MongoDB for prompt metadata & runs  
- UI: React with live diffing and side-by-side output comparison

**Example usage**
- Rapidly refine a "resume summarization" prompt and track improvements across datasets.

---

### 5️⃣ AI-Powered Database Assistant ![sql](https://media.giphy.com/media/l0MYKDrqk6Sx3p7tW/giphy.gif)
**Overview:** Ask your database in plain English; get SQL + answers + auto charts.

**Key features**
- Natural language → SQL translator with explanation steps.  
- Safe preview mode before execution; parameterized queries to avoid injection.  
- Auto-chart suggestions and CSV/JSON export.  
- Schema-aware suggestions and join hints.

**Architecture & Tech**
- LLM translator (prompt → SQL) with schema injection  
- Execution: MySQL/Postgres with audit logs & restricted roles  
- UI: Query preview + result table + quick charting with chartjs

**Example usage**
- “Show top 5 departments by average salary last year” → shows SQL, preview & chart.

---

### 6️⃣ Voice-based AI Personal Assistant (Desktop Control) ![voice]
(https://media.giphy.com/media/3o6Zt8zb1xqX6i6fSg/giphy.gif)
**Overview:** Voice-first assistant that executes desktop automations with a safe sandbox.

**Key features**
- Offline-capable STT (Vosk/Whisper) + local LLM planner.  
- Safe execution: confirm high-risk commands and sandboxed runner.  
- Plugin SDK for adding automations (file ops, browser, terminal tasks).  
- Short-term memory for contextual follow-ups.

**Architecture & Tech**
- STT: Whisper/Vosk; Planner: local LLM; Executor: Python sandbox + PyAutoGUI/Electron bridges  
- UI: Electron app for desktop with micro-interactions & logs

**Example usage**
- “Open my project folder and run the build script” → assistant asks confirmation, then runs the script in isolated environment and streams logs.

---

## 🧰 Tech Stack & Tools
<div align="center">
  <img src="https://skillicons.dev/icons?i=python,js,ts,react,nodejs,express,mongodb,mysql,pytorch,git,docker,vscode&perline=6" />
</div>

**Primary:** JavaScript/TypeScript, Python, React, Node.js, PyTorch, Mistral/LLMs, FFmpeg, Docker, MongoDB/MySQL, Power BI

---

## 🎓 Education
**KGiSL Institute of Technology, Coimbatore**

---

## 📫 Contact
* GitHub: [https://github.com/d3va-12](https://github.com/d3va-12)  
* Email: [devendra99651@gmail.com](mailto:devendra99651@gmail.com)

---

## 🔗 Quick Links
* Profile: [https://github.com/d3va-12](https://github.com/d3va-12)  
* Destiny Dive (project): `/destiny-dive`  
* Frame Interpolation: `/frame-interpolation`  
* Mistral Chatbot: `/mistral-chatbot`  
* Mind Map Generator: `/mindmap-generator`  
* PromptGen: `/promptgen`

---

## ⚡ Footer
Built with curiosity and a drive to make tools that help learners, creators and builders. — Devendra

---

© 2025 Devendra Kumar
