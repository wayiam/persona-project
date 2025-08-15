# Hitesh Choudhary - Creative Chat (Persona Project)

## 🔄 Overview

**Hitesh Choudhary - Creative Chat** is an interactive web-based chat experience that simulates the persona of **Hitesh Choudhary**, a renowned tech educator. Built with **HTML**, **CSS (Tailwind)**, and **JavaScript**, this project integrates **Google's Gemini API** to deliver realistic, Hinglish-style responses, code reviews, simplifications, and even **Text-to-Speech (TTS)** in Hitesh's tone.

## 🛠️ Features

* **Custom Persona Integration**: Predefined dataset & system prompt to replicate Hitesh's communication style.
* **Typewriter & Glitch Effects**: Engaging intro animations with dynamic text.
* **Interactive Chat UI**: Smooth transitions, custom scrollbars, and responsive design.
* **Particle Network Background**: Animated background for visual appeal.
* **Parallax Layers**: Mouse-based parallax movement.
* **Special Action Buttons**:

  * **Get Bhai's Take** 💡: Short, opinionated take on last topic.
  * **Simplify Last Topic** 🧠: Explain concepts simply with analogies.
  * **Code Review** ✨: Analyze code snippets and give constructive feedback.
  * **Generate Code** ✍️: Create code based on user prompts.
  * **Listen to Bhai's Response** 🎧: TTS playback of responses.
* **Modal for Code Generation**: User-friendly interface for requesting generated code.

## 💡 Tech Stack

* **Frontend**: HTML5, CSS3 (TailwindCSS), JavaScript (Vanilla)
* **Animations & Effects**: CSS keyframes, Tailwind utilities
* **APIs Used**:

  * **Gemini 2.5 Flash Preview** for text generation
  * **Gemini 2.5 Flash Preview TTS** for audio output

## 📝 Project Structure

```
project-root/
├── index.html        # Main HTML structure
├── style.css         # Custom styles & animations
├── script.js         # Core JavaScript logic & API calls
```

## 🛠️ Setup & Installation

1. **Clone the Repository**

```bash
git clone <your-repo-url>
cd <project-folder>
```

2. **Open index.html in Browser**
   No build step required. This is a static frontend app.

3. **Configure API Keys**

   * Replace `API_KEY` in `script.js` with your Gemini API key.

4. **Run Locally**
   Simply open `index.html` in your browser or use a local dev server:

```bash
npx live-server
```

## 🌐 Deployment

You can deploy on:

* **GitHub Pages**
* **Vercel**
* **Netlify**

Example for GitHub Pages:

```bash
git add .
git commit -m "Deploy Creative Chat"
git push origin main
gh-pages -d .
```

## 🌟 Future Enhancements

* Dark/Light mode toggle
* More refined TTS with voice customization
* Export chat history
* Mobile optimization for TTS playback

## 👨‍💻 Author

**Saksham Singh**

Inspired by **Hitesh Choudhary**'s teaching style and brand.

---

📁 **License**: MIT License
