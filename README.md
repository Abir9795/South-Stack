# South Stack

**South Stack** is an AI-powered browser IDE and coding assistant built as a CSE327 group project.

Built on top of **Vite**, **React**, and **WebContainers**, South Stack provides a seamless "Plan → Execute → Verify" loop, allowing the AI to not just suggest code, but to understand the entire codebase and verify its changes through real-time build and test feedback.

This portfolio copy is based on the final group branch, `southstack_v1`, from the original group repository: [mubtasimfuad7/southstack](https://github.com/mubtasimfuad7/southstack).

## 🚀 Key Features

- **Senior-Engineer AI Orchestration**: Implements a robust feedback loop for self-correcting code generation.
- **WebContainer Integration**: Fully functional virtual filesystem and terminal running directly in the browser.
- **Advanced Codebase Awareness**: Recursive search and indexing for deep context on complex projects.
- **"Antigravity" Diff Review**: Interactive review process for all AI-proposed changes.
- **P2P Collaboration**: Built-in support for remote debugging and collaborative coding via WebRTC.
- **Vision + Image-to-Design Workflow**: Local vision model support for image-aware UI generation.

## Course Context

South Stack was developed for the CSE327 course as a group project. The Git history includes contributions from Mubtasim Fuad, ShuvoDevDurjoy, Abir, and Misbah.

My primary code contribution was the vision model provider and image-to-design workflow, including the local vision worker, image design orchestration, and related UI integration.

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Build Tool**: [Vite 6](https://vitejs.dev/)
- **Virtual Filesystem**: [WebContainer API](https://webcontainers.io/)
- **Editor**: [Monaco Editor](https://microsoft.github.io/monaco-editor/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **State Management**: [Zustand](https://github.com/pmndrs/zustand)
- **Networking**: [WebRTC](https://webrtc.org/) for P2P AI integration.

## 🏃 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (latest LTS)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Abir9795/South-Stack.git
   cd South-Stack
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
