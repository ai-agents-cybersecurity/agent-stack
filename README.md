# The Agent Stack: Interactive System Map

**An interactive visualization of the 10-layer architecture for reliable AI agents.**

[**🔴 Live Demo**](https://github.com/ai-agents-cybersecurity/agent-stack/mapa_agent_stack.html)) 

---

## 💡 Why I built this
The current discourse around AI agents is often chaotic, treating them as "magic black boxes" or focusing solely on prompt engineering. 

**I built this visual map to ground agent development in solid systems engineering.**

It serves as a mental model to:
1.  **Decompose** complex agentic behaviors into 10 distinct, manageable layers.
2.  **Reframe** the LLM not as a brain, but as a "fallible junior colleague" or "component" within a larger deterministic system.
3.  **Map** old software engineering instincts (like Unit Tests) to their new AI equivalents (like Prompt Regression & Evals).

## 🗺️ The Stack (Mental Model)
The visualization covers the full vertical slice of an agentic system:
-   **Layer 0-1 (Substrate & Model):** The compute and stochastic intelligence.
-   **Layer 2-3 (Prompt & Context):** The ephemeral "program" and working memory.
-   **Layer 4-5 (Tools & Loop):** The bridge to reality and the decision cycle.
-   **Layer 6-8 (Memory, Agents, Orchestration):** State persistence and multi-agent patterns.
-   **Layer 9-10 (Verification & Interface):** Safety checks and user interaction.

## 🚀 Usage
This project is a standalone HTML file (`mapa_agent_stack.html`) powered by `vis.js`.

### Running Locally
1.  Clone the repo.
2.  Open `mapa_agent_stack.html` in any web browser.
3.  Drag nodes to rearrange the view; they will lock in place (physics enabled).

### Deployment
This file is static and can be hosted on GitHub Pages, GitLab Pages, or Vercel with zero configuration.

---

## 🤝 Contributing
If you feel a layer is missing or a concept needs refining, feel free to open an issue or PR. This is a living mental model.
