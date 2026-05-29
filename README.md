# Lumina AI - Interview Prep Copilot

Lumina AI is a comprehensive, interactive platform designed to help users prepare for technical and behavioral interviews. It features AI-driven mock interviews, resume analysis, and a detailed growth tracker to monitor progress over time.

## Features

*   **🎙️ Interview Simulator:** Practice with industry-specific AI avatars (like Ada, Linus, and Alan) that adapt to your tone and technical expertise. Features real-time voice wave animations, mute toggles, and performance metrics.
*   **📄 Resume & Profile Analyzer:** Upload your resume (drag-and-drop support) for instant semantic analysis to optimize your CV for high-tech roles. Includes an interactive optimization checklist and ATS scoring.
*   **📈 Growth Tracker:** Track your confidence, articulation, and technical precision across every practice session using dynamic, interactive charts.
*   **🧭 Modern UI/UX:** Built with Tailwind CSS, featuring glassmorphism aesthetics, dark mode, smooth page transitions, and responsive design.

## Project Structure

*   `index.html`: The main application shell with navigation and UI components.
*   `lumina_ai_interview_simulator/`: Contains the code for the mock interview experience.
*   `lumina_ai_resume_analyzer/`: Contains the code for the resume parsing and feedback tools.
*   `lumina_ai_growth_tracker/`: Contains the code for tracking user performance and history.
*   `lumina_ai_landing_page/`: Contains the standalone landing page design.

## Getting Started

Because the application uses modern web features (like `localStorage` and `postMessage`), it is recommended to run the project using a local web server to avoid browser security restrictions on `file://` protocols.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/lumina-ai.git
    cd lumina-ai
    ```

2.  **Start a local server:**
    If you have Python installed, you can use:
    ```bash
    python -m http.server 8000
    ```
    Or using Node.js:
    ```bash
    npx http-server -p 8000
    ```

3.  **Open the app:**
    Navigate to `http://localhost:8000` in your web browser.

## Technologies Used

*   HTML5
*   Tailwind CSS (via CDN)
*   Vanilla JavaScript
*   Google Fonts & Material Symbols

## License

This project is open-source and available under the [MIT License](LICENSE).
