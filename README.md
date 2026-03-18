# 🎯 Persuasion Engine - v2

An advanced AI-powered application designed to transform any opinion—no matter how unconventional—into a compelling, authoritative, and strategically crafted narrative. By grounding user input in factual research and employing sophisticated psychological framing, the Persuasion Engine builds narratives that are difficult to ignore.

![Persuasion Engine Preview]()

## 🚀 Key Features

- **🧠 Intelligent Opinion Analysis**: Deconstructs user input to identify core themes and extract researchable topics.
- **🔍 Multi-Source Fact-Finding**:
  - **Google Gemini**: Uses built-in Google Search grounding for real-time, high-quality research.
  - **Local/Custom Models**: Supports Tavily API for web search or Wikipedia as a reliable fallback.
- **📋 Strategic Argument Planning**: Generates a step-by-step psychological framework to structure the narrative for maximum impact.
- **✍️ Real-Time Synthesis**: Streams the final polished article with smooth auto-scroll and live progress tracking.
- **🖼️ AI-Powered Illustration**: Generates relevant, high-quality images to visually support the narrative.
- **🛠️ Flexible AI Configuration**:
  - Supports **Google Gemini** (3.1 Pro/Flash) and **Custom OpenAI-compatible APIs** (LM Studio, Ollama).
  - Remembers separate API keys and model preferences for each provider.
- **📄 Professional Export & Preview**:
  - Toggle between **Markdown Preview** and **Raw HTML**.
  - One-click **HTML Export** for immediate publishing.
- **🌓 Adaptive UI**: Fully responsive design with a sophisticated Dark/Light mode.

## 🛠️ Tech Stack

- **Frontend**: React 18+, TypeScript, Vite
- **Styling**: Tailwind CSS (Utility-first styling)
- **Animations**: Motion (formerly Framer Motion)
- **Icons**: Lucide React
- **AI SDK**: `@google/genai` (Google Gemini)
- **Markdown**: `marked` & `react-markdown`

## ⚙️ Configuration

The application is designed to be highly configurable via the built-in **Settings Modal**:

1.  **Google Gemini**: Requires a free API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  **Custom Provider**: Point to any OpenAI-compatible endpoint (e.g., `http://localhost:1234/v1`).
3.  **Search API**: Optionally provide a [Tavily API Key](https://tavily.com) for enhanced web research when using local models.

## 📖 How It Works

1.  **Input**: Enter a message, opinion, or even a "nonsense" statement.
2.  **Analyze**: The AI identifies key topics and performs real-time web research to find supporting facts.
3.  **Plan**: A strategic plan is generated, outlining the psychological framing and structure of the argument.
4.  **Synthesize**: The engine weaves the facts and strategy into a final, persuasive piece of writing.
5.  **Refine**: Use the AI Refinement tool to adjust the tone, length, or style of the output.

