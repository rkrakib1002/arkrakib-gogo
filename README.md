# Typing Master Pro

![Typing Master Pro Screenshot](https://via.placeholder.com/1200x630.png/0f172a/94a3b8?text=Typing+Master+Pro) <!-- Replace with a real screenshot URL -->

**Typing Master Pro** is a modern, interactive touch typing tutor designed to help users learn and master keyboard skills. From basic finger positioning on the home row to typing complex sentences and code snippets, this app provides a comprehensive learning path. It features real-time feedback, detailed performance statistics, AI-powered custom lesson generation, and a gamified achievement system to keep you motivated.

**Live Demo:** [https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/](https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/) <!-- Add your live demo link after deploying -->

---

## ✨ Features

-   **Structured Lessons:** Progress through lessons grouped by difficulty: Beginner, Intermediate, and Advanced.
-   **Visual Hand Guide:** An on-screen hand guide provides intuitive, color-coded feedback for correct finger placement.
-   **Real-time Feedback:** Get instant highlighting of correct and incorrect keystrokes with a blinking caret.
-   **Detailed Stats:** Track your Words Per Minute (WPM), accuracy, error count, and progress over time with an interactive chart.
-   **WPM Goal Setting:** Set personal WPM goals for each session to challenge yourself.
-   **AI-Powered Practice:** Generate infinite, unique practice texts on any topic using the Google Gemini API.
-   **Gamified Achievements:** Unlock badges for reaching milestones (e.g., speed, accuracy, lesson completion) to stay motivated.
-   **Auto-Save Progress:** Your progress in the current lesson is saved automatically, so you can pick up where you left off.
-   **Inactivity Detection:** The timer automatically pauses when you take a break, ensuring your WPM score remains accurate.
-   **Fully Responsive:** A sleek and modern interface that works beautifully on all devices.
-   **SEO Friendly:** Optimized for search engines to ensure discoverability.

---

## 📲 Installation (PWA)

This application is a Progressive Web App (PWA), which means you can install it on your device for an app-like experience with offline access.

-   **On Desktop (Chrome/Edge):** Open the app in your browser. Look for an "Install" icon (usually a computer with a down arrow) in the address bar. Click it to install the app.
-   **On Mobile (iOS/Android):** Open the app in your browser (Safari on iOS, Chrome on Android). Use the "Share" menu and find the "Add to Home Screen" option.

This will add a "Typing Master Pro" icon to your home screen or app launcher.

---

## 🛠️ Tech Stack

-   **Frontend:** React, TypeScript, Tailwind CSS
-   **Charts:** Recharts
-   **AI:** Google Gemini API (`@google/genai`)

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have a modern web browser. No local installation of Node.js or any package manager is required, as this project uses ES modules and an `importmap` to load dependencies directly from a CDN.

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
    cd YOUR_REPO_NAME
    ```

2.  **Set up your API Key (Optional):**
    The "Generate Custom Text with AI" feature uses the Google Gemini API. To enable this feature, an API key must be available as an environment variable named `API_KEY`. The application's core functionality will work without it, but the AI generation feature will be unavailable.
    
    - You can get a free API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
    - How you set the environment variable depends on your development setup. If you are using a bundler like Vite or Create React App, you can create a `.env` file in the project root.
    
    **Important:** For security, do not commit your API key to a public repository. If you use a `.env` file, ensure it is listed in your `.gitignore` file.

3.  **Run the application:**
    Since this is a static project, you can open the `index.html` file directly in your browser. However, for the best experience, it's recommended to serve it with a simple local server.

    If you have Python installed:
    ```sh
    # Python 3
    python -m http.server
    ```
    Then, open your browser and navigate to `http://localhost:8000`.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
