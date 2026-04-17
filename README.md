# AI-Driven-SOC-Architecture
 An interactive, AI-powered visualization tool exploring the architecture of a modern Security Operations Center—featuring Edge SLMs, Agentic LLMs, RAG, and the Model Context Protocol (MCP).

📖 Overview

The Next-Gen AI-Driven SOC Architecture Explorer is a single-page interactive application designed for Cybersecurity Architects, CISOs, and Systems Engineers. It visualizes how modern enterprise security must evolve from deterministic, rule-based systems into hyper-automated, agentic AI ecosystems to combat machine-speed attacks.

This tool doesn't just show static diagrams; it integrates directly with the Google Gemini API to run live, AI-driven attack simulations against the architecture and generate dynamic, contextual explanations for every component.

✨ Key Features

Interactive Dual-Views: Toggle seamlessly between the Logical Architecture (data flow and reasoning funnels) and the Technical Deployment (Kubernetes, VPCs, Kafka, vLLM).

Multi-Disciplinary Perspectives: Built to reflect the needs of the entire enterprise, including specific components for the Red Team (BAS, Deception), Blue Team (UEBA, Hunting), GRC (Sovereignty, Policy-as-Code), and Enterprise Architecture (iPaaS, FinOps Routing).

Live AI Attack Simulator: Input any hypothetical threat scenario (e.g., Insider threat exfiltrating data via DNS tunneling) and the Gemini API will dynamically simulate how this specific architecture detects, analyzes, and mitigates the attack.

AI Explainers (Simplify vs. Deep Dive): Select any component and ask the AI to explain it like you're 5 years old (ELI5), or generate a highly technical deep-dive for Senior Engineers.

🚀 Getting Started

This project is a 100% client-side, zero-dependency HTML file.

Clone the repository or download soc_interactive.html.

Open soc_interactive.html in any modern web browser.

To use the AI Features: Click the 🔑 Key icon in the top navigation bar to configure your API key.

Note: The app uses a secure "Bring Your Own Key" (BYOK) model. Your key is stored locally in your browser's localStorage and is never sent to any server other than the Google Gemini API.

🛠️ Tech Stack

Frontend: HTML5, Vanilla JavaScript

Styling: Tailwind CSS (via CDN)

Icons: Lucide Icons

AI Integration: Google Gemini API (gemini-2.5-flash)

🏷️ Repository Tags / Topics

cybersecurity soc-architecture agentic-ai llm slm rag mcp infosec gemini-api interactive-diagram
