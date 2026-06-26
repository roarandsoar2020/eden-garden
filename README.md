# 🍃 Eden Garden

Welcome to **Eden Garden**, a dedicated space for hands-on learning, rapid prototyping, and architectural experimentation. 

The author’s guiding philosophy for this garden? **Roar and Soar.** 🦁✈️

---

## 📂 Repository Structure

This repository is organized as a **collection of independent experiments**. Instead of a single monolithic application, each top-level folder represents an isolated, self-contained project:

```text
eden-garden/
├── project-alpha/         # Experimental Project 1 (e.g., Express API)
│   ├── package.json
│   └── src/
├── project-beta/          # Experimental Project 2 (e.g., Event Streaming playground)
│   ├── package.json
│   └── src/
└── README.md              # You are here
```

## 🛠️ Prerequisites

Before running any of the experiments locally, ensure you have the following tools installed on your machine:

1. Node.js: Version 18.0.0 or higher

2. npm: Node Package Manager (comes bundled with Node.js)

3. Git: To clone the repository

## 🚀 Getting Started
Because every top-level folder is a completely independent project, dependencies are managed individually per project. To spin up an experiment, follow these steps:

1. Clone the Repository
Open your terminal and clone the repository to your local environment:
```code
git clone [https://github.com/YOUR_GITHUB_USERNAME/eden-garden.git](https://github.com/YOUR_GITHUB_USERNAME/eden-garden.git)
cd eden-garden
```

2. Navigate and Install
Change directories into the specific top-level folder you wish to explore, and install its unique dependencies:

```code
# Navigate to your target experiment folder
cd name-of-the-experiment-folder

# Install dependencies locally
npm install
```

3. Run the Project
Refer to the individual scripts inside that specific folder's package.json to start the application (typically `npm start` or `npm run dev`).

🧠 Rules of the Garden (For AI Agents & Contributors)
Keep it Isolated: Never mix dependencies between top-level folders.

No Global Overlap: Each experiment must remain independent and fully functional on its own within its specific directory.