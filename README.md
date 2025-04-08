# 🎙️ Tactara Voice Agent for Customer Support

**Conversational support, reimagined with OpenAI.**

Tactara’s Voice Agent is a plug-and-play AI application that transforms your documentation into a real-time voice assistant for customer support. Built on OpenAI's GPT-4o and Text-to-Speech (TTS) stack, this system crawls through technical docs, generates semantic embeddings, and delivers answers in natural-sounding speech — all through a clean Streamlit UI.

---

## 🚀 Why Teams Choose Tactara

### 🧠 Smart Knowledge Base Creation  
- Crawls documentation using [Firecrawl](https://firecrawl.dev/)  
- Parses and stores structured data in [Qdrant](https://qdrant.tech/)  
- Embeddings via FastEmbed for lightning-fast semantic search

### 🤖 Modular AI Agent Architecture  
- **Documentation Processor:** Translates structured docs into clear, human-readable answers  
- **TTS Agent:** Converts answers into lifelike speech with adjustable voice options  
- **Voice Customization:** Choose from multiple OpenAI voices like `nova`, `shimmer`, `onyx`, and more

### 🧑‍💻 Developer-Friendly Interface  
- Built with Streamlit for quick deployments  
- Audio player with download support  
- Live progress indicators for transparency during processing

---

## 🛠️ Quickstart

### 1. Clone the Repo

```bash
git clone https://github.com/Tactara/customer_support_voice_agent.git
cd customer_support_voice_agent
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Your API Keys  
You'll need credentials from:
- [OpenAI](https://platform.openai.com/)
- [Qdrant Cloud](https://qdrant.tech/)
- [Firecrawl](https://firecrawl.dev/)

Update the config or input via the sidebar UI.

### 4. Launch the App

```bash
streamlit run customer_support_voice_agent.py
```

---

## 💬 Using the Voice Agent

- Enter your API keys via the Streamlit sidebar  
- Paste a documentation URL (limit: 5 pages per crawl)  
- Select a voice from the dropdown  
- Click “Initialize System”  
- Ask a question → Get spoken + written answers in real time

---

## 🔍 Under the Hood

| Feature | Description |
|--------|-------------|
| 🔗 **Firecrawl** | Smart crawler that preserves structure & metadata |
| 🧬 **FastEmbed + Qdrant** | Fast, semantic vector search for matching content |
| 🗣️ **OpenAI TTS** | Natural-sounding responses with customizable voices |

---

## 🧩 Ideal For

- Cloud Service Providers needing automated Tier-1 support  
- Internal IT teams seeking self-service documentation tools  
- Developer platforms with complex user documentation

---

**Built with ❤️ by [Tactara](https://www.tactara.ai)**
