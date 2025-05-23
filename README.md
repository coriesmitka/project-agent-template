# 🧠 Project Agent — AI & Us: Exploring Human + Machine Thought

**Project Agent** is a reflective, AI-powered writing assistant designed to explore how artificial intelligence is reshaping not just what we do — but how we think.

Created as a dialogic partner, this agent generates LinkedIn-ready posts centered around the societal, cognitive, and ethical implications of AI. It’s not about hype — it’s about *human agency, peace, and perspective in the age of algorithms*.

---

## ✨ Purpose

While most AI tools aim to increase productivity, **Project Agent** exists to slow down, ask better questions, and help surface insights around:

- 🧠 Cognitive evolution and AI’s role in how we think
- 📱 Everyday behaviors like scrolling, searching, and passive confirmation
- 🔍 Underexplored questions about trust, reflection, and ethical automation

It’s built with care — guided by personal experience, quiet thought, and the belief that fewer than 1% of people are thinking about this... but maybe more should be.

---

## 📂 Project Structure

- `project-agent/`
  - `input/` – Content prompts
    - `seeds.json`
  - `output/` – AI-generated drafts
    - `generated_posts/`
    - `review_queue/`
  - `agent/` – Core logic and templates
    - `generator.py`
    - `prompt_template.txt`
  - `logs/` – Optional event logs
    - `agent.log` or `.gitkeep`
  - `tests/` 
    - `test_generator.py`
  - `config.ini` – API keys & settings (excluded from versioning)
  - `README.md` – This file

---

## 🧰 Technologies

- Python (lightweight modular structure; no formal framework used)
- OpenAI SDK v1.x (client-based API access with GPT-3.5/GPT-4 compatibility)
- JSON-based content seeding
- CSV-based logging and review tracking
- CLI-driven generation (no web or UI framework at this stage)
- Optional integrations (e.g., Notion API, publishing tools)

## 🧱 Architecture Notes

Project Agent is intentionally built with a **lightweight, framework-free structure** using core Python. This ensures clarity, portability, and full control over each step in the AI post-generation workflow.

The current design favors:
- Transparency over abstraction
- File-based drafts over database dependency
- Manual review before automation

## 🚀 Extensibility Options

Project Agent can be extended modularly without disrupting the current workflow:

- **FastAPI / Flask** — expose the agent as a web service or REST API
- **Streamlit / Gradio** — add a visual interface to review or generate posts
- **Notion / LinkedIn API** — integrate for scheduling or automated publishing
- **Typer / Argparse** — structure generation logic into a CLI tool
- **SQLite / JSONL** — replace flat files with versioned storage or searchable history


---

## 📌 Notes

- This project is built gradually, by intention — not automation.
- All content is reviewed before posting, and public publishing is done only via LinkedIn.
- The tone is reflective, non-alarmist, and rooted in real personal experience.

---
## :clipboard: Project Status

| Module      | Description                                 | Status        |
|-------------|---------------------------------------------|----------------|
| Module 1    | Project Charter + Voice Definition          | ✅ Completed    |
| Module 2    | Content Strategy + seeds.json created       | ✅ Completed    |
| Module 3    | Prompt Template + Agent Voice Design        | ✅ Completed    |
| Module 4    | Post Generator Script (generator.py)        | ✅ Completed    |
| Module 4.5  | Component Validation (API, template, seed)  | ✅ Completed  |
| Module 5    | Review + Draft Output Workflow              | ⬜ Not Started  |
| Module 6    | (Optional) Comment Summarizer               | ⬜ Planned      |


### ✅ Testing Status

| Test Type               | Description                                           | Status        |
|-------------------------|-------------------------------------------------------|----------------|
| Unit Test (Bypass Mode) | Verified generator script runs end-to-end without API | ✅ Completed    |
| SIT (Full Flow)         | Pending live OpenAI generation & output verification  | ⬜ Pending      |

---

## 📎 Note on Perspective

This project is a personal exploration into the quiet impacts of AI on how we think. No hype — just reflection.

I’m not a neuroscientist, AI researcher, or ethicist. I’m a technologist and a reflective thinker, using lived experience and curiosity to ask how AI may be shaping the way we think, choose, and relate to the world.

All reflections are written with care, not credentials — and every post invites thought, not conclusions.

---

---


