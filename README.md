# 🏎️ AlgoRace

AlgoRace is a dynamic programming competition platform where speed meets intelligence. Participants compete in real-time to solve algorithmic challenges, which are instantly evaluated and scored by an **AI Judge** powered by Google Gemini 2.0 Flash.

![AlgoRace Banner](https://via.placeholder.com/1200x400?text=AlgoRace+-+AI+Powered+Coding+Competitions)

## 🌟 Key Features

- **🏆 Real-time Competitions:** Create and join rooms to compete with others instantly.
- **🤖 AI Judging:** Submissions are automatically evaluated by Gemini 2.0 Flash for correctness, logic, and efficiency.
- **📝 Live Code Editor:** A fully integrated Monaco Editor (the power behind VS Code) for a seamless coding experience.
- **📊 Dynamic Leaderboard:** Track your progress and see how you rank against other participants in real-time.
- **🛠️ Customizable Challenges:** Define your own problem subjects, constraints, time limits, and preferred languages.
- **⚡ Modern Tech Stack:** Built with React, Vite, Tailwind CSS, and Node.js for a fast and responsive experience.

## 🧠 How the AI Judge Works

AlgoRace leverages the **Gemini 2.0 Flash** model to provide objective and nuanced scoring. Unlike traditional unit-test-based judges, our AI judge can:
1.  **Understand Intent:** Evaluate the logic even if edge cases are missed.
2.  **Language Awareness:** Check if the submission adheres to the requested programming language.
3.  **Provide Feedback:** Offer concise, constructive feedback on how to improve the code.
4.  **Handle Flexible Problems:** Grade subjective or open-ended algorithmic challenges that are hard to test with static inputs.

## 🛠️ Tech Stack

### Frontend
- **Framework:** [React](https://reactjs.org/) (with [Vite](https://vitejs.dev/))
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **State Management:** [Jotai](https://jotai.org/)
- **Editor:** [@monaco-editor/react](https://github.com/suren-atoyan/monaco-react)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Icons:** [Lucide React](https://lucide.dev/)

### Backend
- **Runtime:** [Node.js](https://nodejs.org/)
- **Server:** [Express](https://expressjs.com/)
- **Real-time Communication:** [Socket.io](https://socket.io/)
- **AI Integration:** [Google Generative AI (Gemini API)](https://ai.google.dev/)

## 🚀 Getting Started

### Prerequisites
- [Bun](https://bun.sh/) (preferred) or [Node.js](https://nodejs.org/) (v18+)
- A [Google AI API Key](https://aistudio.google.com/app/apikey)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/algorace.git
    cd algorace
    ```

2.  **Install dependencies:**
    ```bash
    bun install
    # or
    npm install
    ```

3.  **Environment Variables:**
    Create a `.env` file in the `algorace/` root directory:
    ```env
    PORT=3000
    GOOGLE_AI_API_KEY=your_gemini_api_key_here
    ```

### Running the Application

For development, you'll need to run both the backend and the frontend.

**1. Start the Backend Server:**
```bash
bun run server
# or
node server/index.js
```

**2. Start the Frontend Application:**
```bash
bun run start
# or
npm run start
```

By default:
- Frontend will be available at `http://localhost:5173` (during dev) or served via `http://localhost:3000` (after build).
- Backend runs on `http://localhost:3000`.

## 📸 Screenshots

| Home Page | Competition Lobby |
| :---: | :---: |
| ![Home](https://via.placeholder.com/400x250?text=Home+Page) | ![Lobby](https://via.placeholder.com/400x250?text=Lobby) |

| Coding Environment | Results Table |
| :---: | :---: |
| ![Editor](https://via.placeholder.com/400x250?text=Code+Editor) | ![Results](https://via.placeholder.com/400x250?text=Leaderboard) |

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Built with ❤️ by [AnriHasani](https://github.com/AnriHasani)
