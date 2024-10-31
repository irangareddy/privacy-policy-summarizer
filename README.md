# Privacy Policy Summarizer 📜

A powerful tool that simplifies privacy policies into easy-to-understand summaries using OpenAI's GPT. Available in both Streamlit and Gradio implementations.

## Features ✨

- Privacy policy text analysis and summarization
- Multiple summary styles (simple, detailed, concerns)
- OpenAI GPT-powered interpretation
- Download summaries as text files
- Cross-platform implementations

## Prerequisites 🛠️

- Python 3.12 or higher
- OpenAI API key
- Task (go-task) for running commands

## Quick Start 🚀

1. **Clone the repository**
```bash
git clone https://github.com/irangareddy/privacy-policy-summarizer.git
cd privacy-policy-summarizer
```

2. **Install dependencies**
```bash
task install
```

3. **Set up environment variables**
```bash
cp .env.example .env
# Edit .env and add your OpenAI API key
```

4. **Run the application**

For Streamlit version:
```bash
task streamlit:app
```

For Gradio version:
```bash
task gradio:app
```

## Usage 💡

1. **Streamlit Interface (Default port: 8501)**
   - Enter your OpenAI API key in the sidebar
   - Paste privacy policy text in the input area
   - Select summary style
   - Click "Summarize" to generate summary
   - Download results using the download button

2. **Gradio Interface (Default port: 8502)**
   - Enter privacy policy text