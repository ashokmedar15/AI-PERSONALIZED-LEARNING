# AI-Powered Educational Platform

A modern, AI-powered educational platform built with Next.js, designed to provide personalized learning experiences, adaptive content, and intelligent tutoring for students and lifelong learners.

## 🚀 Features

- **AI Educational Counselor**: Get real-time guidance, study strategies, and career advice from an AI assistant.
- **Personalized Learning Paths**: Adaptive lessons tailored to your learning style, level, and goals.
- **Interactive Lessons**: Step-by-step educational content with notes, videos, and practice problems.
- **Multi-Subject Support**: Mathematics, Physics, Computer Science, Biology, Chemistry, and more.
- **Progress Tracking**: Monitor your learning progress and achievements.
- **Modern UI**: Responsive design using Tailwind CSS and shadcn/ui components.
- **API Integration**: All educational content and chatbot features are powered by Next.js API routes.

## 🛠️ Tech Stack

- **Next.js 14** (App Router)
- **TypeScript**
- **Tailwind CSS**
- **shadcn/ui**
- **Groq AI API** (for chatbot)

## 📦 Project Structure

```
app/
  api/                # Next.js API routes (chatbot, educational content, personalization)
  dashboard/          # Main dashboard page
  lesson/             # Lesson page with step-by-step content
  login/              # Authentication page
  globals.css         # Global styles
  layout.tsx          # App layout
components/
  ai-chatbot.tsx      # Main chatbot component
  ai-educational-counselor.tsx # Floating AI chat button
  auth-provider.tsx   # Authentication context
  content-generator.tsx # Content generation logic
  ui/                 # UI components (button, card, input, etc.)
lib/
  utils.ts            # Utility functions
```

## ⚡ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ashokmedar15/AI-powered-educational-platform.git
   cd AI-powered-educational-platform
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up environment variables:**
   - Copy `.env.example` to `.env.local` and add your `GROQ_API_KEY` (get it from https://console.groq.com/)
4. **Run the development server:**
   ```bash
   npm run dev
   ```
   The app will be available at [http://localhost:3000](http://localhost:3000)

## 🌐 Deployment

- Deploy easily to [Vercel](https://vercel.com/) by importing your GitHub repository and setting the `GROQ_API_KEY` environment variable.
- See `DEPLOYMENT_GUIDE.md` for step-by-step deployment instructions.

## 📚 Documentation

- See `SETUP_INSTRUCTIONS.md` for local setup and environment configuration.
- See `DEPLOYMENT_GUIDE.md` for Vercel deployment steps.
- See `GITHUB_SETUP_GUIDE.md` for repository management tips.

## 🤖 AI Chatbot Usage

- The AI Educational Counselor is available on all pages via the floating chat button.
- The chatbot uses the Groq API for intelligent, context-aware responses.

## 📝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License.

---

**AI-Powered Educational Platform** – Personalized, adaptive, and intelligent learning for everyone.
