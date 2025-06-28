# AI-Powered Educational Platform

A modern, AI-powered educational platform built with Next.js, designed to provide personalized learning experiences, adaptive content, and intelligent tutoring for students and lifelong learners.

## 🚀 Features

- **AI Educational Counselor**: Get real-time guidance, study strategies, and career advice from an AI assistant.
- **Personalized Learning Paths**: Adaptive lessons tailored to your learning style, level, and goals.
- **Interactive Lessons**: Step-by-step educational content with notes, videos, and practice problems.
- **Multi-Subject Support**: Mathematics, Physics, Computer Science, Biology, Chemistry, and more.
- **Progress Tracking**: Monitor your learning progress and achievements.
- **Responsive Design**: Modern UI built with Tailwind CSS and shadcn/ui.
- **Real-time AI Integration**: Live chat with educational AI assistant.

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, shadcn/ui components
- **AI Integration**: Groq AI API for intelligent responses
- **Deployment**: Vercel (recommended)
- **Package Manager**: npm

## 📁 Project Structure

```
personalized-quiz-generator/
├── app/                    # Next.js app directory
│   ├── api/               # API routes
│   │   ├── chatbot/       # AI chatbot API
│   │   ├── educational-content/  # Educational content API
│   │   └── personalize-content/  # Content personalization API
│   ├── dashboard/         # Dashboard page
│   ├── lesson/           # Lesson page
│   ├── login/            # Login page
│   ├── globals.css       # Global styles
│   ├── layout.tsx        # Root layout
│   └── page.tsx          # Home page
├── components/            # React components
│   ├── ui/               # shadcn/ui components
│   ├── ai-chatbot.tsx    # AI chatbot component
│   ├── ai-educational-counselor.tsx  # Educational counselor
│   └── content-generator.tsx  # Content generation
├── lib/                  # Utility functions
└── public/               # Static assets
```

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Groq AI API key (get from [console.groq.com](https://console.groq.com/))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ashokmedar15/AI-powered-educational-platform.git
   cd AI-powered-educational-platform
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp env.example .env.local
   ```
   
   Edit `.env.local` and add your Groq API key:
   ```
   GROQ_API_KEY=your_groq_api_key_here
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📚 Available Subjects

- **Mathematics**: Algebra, Calculus, Geometry, Statistics
- **Physics**: Mechanics, Thermodynamics, Electromagnetism, Quantum Physics
- **Computer Science**: Programming, Data Structures, Algorithms, Web Development
- **Biology**: Cell Biology, Genetics, Ecology, Human Anatomy
- **Chemistry**: Organic Chemistry, Inorganic Chemistry, Biochemistry
- **Literature**: Poetry, Prose, Drama, Literary Analysis

## 🎯 Key Features Explained

### AI Educational Counselor
- Real-time chat with AI assistant
- Study strategy recommendations
- Career guidance and advice
- Subject-specific help
- Learning technique suggestions

### Personalized Learning
- Adaptive content based on learning style
- Difficulty level adjustment
- Progress tracking
- Customized learning paths
- Interactive exercises

### Interactive Lessons
- Step-by-step explanations
- Video resources
- Practice problems
- External resources
- Progress indicators

## 🚀 Deployment

### Deploy to Vercel (Recommended)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Deploy on Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Add environment variable: `GROQ_API_KEY`
   - Deploy!

### Environment Variables

- `GROQ_API_KEY`: Your Groq AI API key (required)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) for the amazing React framework
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [shadcn/ui](https://ui.shadcn.com/) for the beautiful component library
- [Groq AI](https://groq.com/) for the AI API services

## 📞 Support

If you have any questions or need help, please open an issue on GitHub or contact the maintainers.

---

**Made with ❤️ for better education**
