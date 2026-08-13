# AI-Powered Mock Interview Platform

An AI-powered full-stack web application designed to help users practice job interviews in a realistic and interactive environment. The platform allows users to participate in AI-driven interviews through text and voice interaction and receive personalized feedback based on their responses.

## 🚀 Features

* User registration and authentication
* AI-generated interview questions
* Technical and behavioral interview modes
* Real-time voice-based interview interaction
* Text-based interview interaction
* AI-powered response analysis
* Personalized interview feedback
* Interview transcripts
* Performance scoring
* Strengths and areas-for-improvement analysis
* Interview history and dashboard
* Responsive user interface

## 🛠️ Technologies Used

### Frontend

* Next.js
* React
* Tailwind CSS
* shadcn/ui

### Backend and Database

* Firebase
* Firebase Authentication
* Firebase data storage

### Artificial Intelligence

* Google Gemini
* Natural Language Processing (NLP)

### Voice Interaction

* Vapi AI
* Speech-to-Text
* Text-to-Speech

### Validation

* Zod

## 🏗️ System Architecture

The application integrates multiple technologies:

**Next.js + React → User Interface**

**Firebase → Authentication and Data Management**

**Google Gemini → AI Question Generation and Response Analysis**

**Vapi AI → Real-Time Voice Interview Interaction**

**Zod → Input Validation**

## 🤖 AI Interview Process

1. User selects the job role, experience level, interview type, and technology stack.
2. The application generates interview questions using Google Gemini.
3. The user answers questions through text or voice.
4. Vapi AI enables real-time voice interaction.
5. The interview transcript is collected.
6. Google Gemini analyzes the responses.
7. The system generates scores and personalized feedback.
8. The user can review strengths and areas for improvement.

## 📊 Feedback System

The platform evaluates candidates across multiple categories:

* Communication Skills
* Technical Knowledge
* Problem-Solving
* Cultural & Role Fit
* Confidence & Clarity

Each category receives a score out of 100 along with detailed feedback.

## 💻 Project Structure

```text
app/
components/
context/
lib/
models/
public/
middleware.ts
package.json
README.md
```

## ⚙️ Installation

### Prerequisites

* Node.js
* npm

### Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Powered-Mock-Interview-Platform.git
cd AI-Powered-Mock-Interview-Platform
```

### Install dependencies

```bash
npm install
```

### Environment Variables

Create a `.env.local` file in the project root and configure the required API keys and Firebase credentials.

Do not commit `.env.local` or expose API keys publicly.

### Run the application

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

## 🎯 Project Objective

The objective of this project is to provide an accessible AI-powered platform for interview preparation. It combines full-stack web development, generative AI, voice interaction, authentication, and data management to create an interactive mock interview experience.

## 👨‍💻 Project Role

**Full Stack Developer**

Worked on frontend interfaces, backend integration, AI functionality, voice interaction, authentication, data handling, validation, and overall application integration.

## 📌 Future Enhancements

* Advanced performance analytics
* More interview categories
* Resume-based interview generation
* Improved AI evaluation
* Multi-language interview support
* Interview progress tracking

