# Agent Instructions for Eden Garden

## 📂 Repository Architecture
- This is a multi-project repository for isolated technical learning and experimentation.
- **Strict Rule:** Every top-level folder must remain completely independent. 
- Never install global npm packages or mix dependencies across different project folders.
- Each project must contain its own unique configurations, source files, and context.

## 🔄 Git & Workflow Rules
- **Strict Rule:** Agents must **never** commit or push changes directly to the `main` branch.
- Always isolate any new feature, bug fix, or project inside a **separate feature branch**.
- Once a task is complete, the agent must **raise a Pull Request (PR)** to `main` for human review and approval.

## 🛠️ General Tech Stack Preferences
- **Runtime:** Node.js 18+ (LTS)
- **Frontend Architecture:** - For lightweight/single-file prototypes: Clean vanilla HTML5, CSS, standard Canvas, or Three.js via stable CDNs.
  - For scalable applications: Modern **React.js** (typically initialized via Vite or Next.js inside that project's folder).
- **Backend Architecture:** - For standalone microservices or APIs: **Express.js** using modular TypeScript.
  - For full-stack applications: **Next.js** using its native API routes and App Router infrastructure.

## 🤖 Behavior Guidelines
- Prioritize clean, performant, and self-documenting code.
- Always include comments explaining architectural choices or math formulas used in simulations/games.
- When adding a feature or fixing a bug, do not alter unrelated folders or experiments.