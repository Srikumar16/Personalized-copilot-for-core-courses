# Personalized Learning Copilot (DSA & DBMS)

A chat-based educational platform built for the Hackathon MVP using **Next.js 14** and **Firebase**.

## 🚀 Features

- **Personalized Learning Path**: Select between DSA or DBMS and choose your proficiency level.
- **AI Chatbot Tutor**: Rule-based chatbot that explains concepts and interacts with you.
- **Interactive Quizzes**: MCQs after every topic to test understanding.
- **Real-time Progress**: Track your course progress in the sidebar.
- **Dual Authentication**: Sign in via Google or Phone (OTP). 
- **Demo Mode**: "Skip Login" feature for easy testing and judging without credentials.

## 🛠️ Tech Stack

- **Frontend**: Next.js 14 (App Router), TypeScript, Vanilla CSS.
- **Authentication**: Firebase Auth.
- **State Management**: React Context API.
- **Deployment**: Vercel (Recommended).

## 📂 Project Structure

```bash
├── src/
│   ├── app/              # Next.js App Router pages
│   ├── components/       # Reusable UI components
│   ├── hooks/            # Custom logic hooks (Chat engine)
│   ├── lib/              # Utilities (Firebase config, Curriculum data)
│   └── styles/           # Global styles
├── public/               # Static assets
└── ...
```

## ⚡ Getting Started

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd personal-learning-copilot
```

### 2. Install dependencies
```bash
npm install
```

### 3. Setup Environment Variables
Create a `.env.local` file in the root directory:
```env
NEXT_PUBLIC_FIREBASE_API_KEY=your_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```
> **Note**: If you don't have keys, you can use the **Demo Mode** in the app to skip login.

### 4. Run the development server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🤝 Contributing

This is a Hackathon MVP. Feel free to fork and improve!

## 📄 License

MIT
