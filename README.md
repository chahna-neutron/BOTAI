# ✨ Cognifile AI

> A multimodal AI assistant that lets you interact with AI through text, PDFs, and images — all from one interface.

## 🚀 Overview

**Cognifile AI** is a multimodal AI assistant designed to provide a single interface for interacting with different types of content.

Instead of using separate tools for chatting, reading documents, analyzing images, and generating images, Cognifile AI brings these capabilities together in one application.

Users can ask questions, upload PDFs or images for analysis, and generate images using natural-language prompts.

---

## 🌐 Live Demo

🚀 **Try Cognifile AI:** https://valiant-possibility-production-e434.up.railway.app

---

## ✨ Features

### 💬 AI Chat

Ask questions and have natural conversations with the AI.

### 📄 PDF Analysis

Upload a PDF and ask questions about its content.

Cognifile AI processes the uploaded document and provides answers based on the information available in the document.

### 🖼️ Image Analysis

Upload an image and ask the AI to analyze or explain its contents.

### 🎨 Image Generation

Describe an image using natural language and generate an AI-created image.

### 🧠 Multiple Modes

Cognifile AI provides different modes for different use cases:

- 🧠 **Normal Mode** — General-purpose AI assistance
- 🎯 **Interview Mode** — Helps with interview-related questions and preparation
- 📝 **Resume Mode** — Assists with resume-related tasks and career preparation

### 🌐 Web Interface

Cognifile AI provides a clean and responsive web interface where users can access all the features from a single application.

---

## 🛠️ Tech Stack

### Backend

- Python
- Flask
- REST APIs

### Frontend

- HTML
- CSS
- JavaScript

### AI

- Generative AI APIs
- Multimodal AI
- Large Language Models
- Image Generation

### Deployment

- Railway
- GitHub

---

## 🏗️ Project Structure

```text
BOTAI/
├── static/
│   ├── generated/      # Stores generated images and assets
│   ├── uploads/        # Uploaded PDFs and images
│   ├── script.js       # Client-side chat logic and mode toggles
│   └── style.css       # UI layout and styling
├── templates/
│   └── index.html      # Main user interface
├── .env                # API keys and secret variables (ignored by Git)
├── .gitignore
├── app.py              # Flask server and AI API integration
└── requirements.txt    # Python dependencies
```

---

## ⚙️ How It Works

The application follows a simple workflow:

```text
             ┌─────────────────────┐
             │      User Input     │
             └──────────┬──────────┘
                        │
          ┌─────────────┼─────────────┐
          │             │             │
          ▼             ▼             ▼
       Text           PDF           Image
          │             │             │
          └─────────────┼─────────────┘
                        │
                        ▼
              ┌──────────────────┐
              │   AI Processing  │
              └────────┬─────────┘
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
       Answer       Analysis    Image Generation
          │            │            │
          └────────────┼────────────┘
                       ▼
              ┌──────────────────┐
              │   User Response  │
              └──────────────────┘
```

---

## 🖥️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/chahna-neutron/BOTAI.git
cd BOTAI
```

### 2. Set Up a Virtual Environment

**macOS/Linux:**

```bash
python3 -m venv venv
source venv/bin/activate
```

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory:

```env
API_KEY=your_api_key_here
```

> ⚠️ Never commit your `.env` file or API keys to GitHub.

### 5. Run the Application

```bash
python app.py
```

Then open the local URL shown in your terminal.

---

## 🔐 Environment Variables

Cognifile AI uses environment variables for API credentials and configuration.

Example:

```env
API_KEY=your_api_key_here
```

Make sure `.env` is included in `.gitignore`.

---

## 🎯 Use Cases

Cognifile AI can be used for:

- 📚 Studying and learning
- 📄 Understanding PDF documents
- 🔍 Image analysis
- 🎨 Creative image generation
- 💼 Interview preparation
- 📝 Resume assistance
- 💬 General AI conversations

---

## 👩‍💻 Author

**Chahna Sri G**

Computer Science Engineering Student

### Interests

- Artificial Intelligence
- Full-Stack Development
- Generative AI
- Software Development

---

## 📄 License

This project is licensed under the MIT License.
