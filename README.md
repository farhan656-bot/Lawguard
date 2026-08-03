# LawGuard AI: Autonomous Multi-Source Legal & Contract Review Agent

LawGuard AI is an open-source, multi-agent legal compliance and contract review system built using the **AntiGravity** orchestration framework and powered by **Anthropic's Claude API**.

## 🏗️ Architecture & Agentic Workflow

LexiGuard leverages AntiGravity to manage sequential and parallel agent workflows:

1. **Document Ingestion Agent:** Extracts and structures text from legal PDFs/DOCX documents.
2. **Risk & Compliance Agent (powered by Claude):** Identifies high-risk clauses, indemnities, liability traps, and non-standard terms.
3. **Policy Cross-Reference Agent:** Checks contract clauses against standard regulatory frameworks or company policies.
4. **Redaction & Advisory Agent:** Generates clear, human-readable risk summaries and proposed contract edits (redlines).

## 🛠️ Tech Stack

- **Orchestration:** AntiGravity Framework
- **Core LLM Engine:** Anthropic Claude API (Claude 3.5 Sonnet)
- **Language:** Python 3.10+
- **License:** MIT License

## 🚀 Getting Started

*(Work in Progress - Initial Setup)*

```bash
git clone [https://github.com/YOUR_USERNAME/LexiGuard-AI.git](https://github.com/YOUR_USERNAME/LexiGuard-AI.git)
cd LexiGuard-AI
pip install -r requirements.txt# Lawguard
