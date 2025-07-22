# AI Resume Analyzer (Hirelytics)

Hirelytics is a modern web application that provides smart, AI-powered feedback for resumes, helping job seekers optimize their applications for Applicant Tracking Systems (ATS) and improve their chances of landing interviews.

## Features
- **Resume Upload**: Easily upload your resume in PDF format.
- **ATS Analysis**: Get an ATS score and actionable tips to improve your resume's compatibility with automated screening systems.
- **Detailed Feedback**: Receive scores and suggestions for Tone & Style, Content, Structure, and Skills.
- **Visual Summaries**: View your resume's strengths and weaknesses with intuitive gauges and badges.
- **Application Tracking**: Track all your uploaded resumes and their feedback in one place.
- **Authentication**: Secure login to manage your resume data.
- **Data Management**: Option to wipe all stored data securely.

## Tech Stack
- **Frontend**: React 19, TypeScript, Tailwind CSS
- **Routing**: React Router v7
- **State Management**: Zustand
- **PDF Processing**: pdfjs-dist
- **AI Integration**: Puter.js (for AI feedback and file management)
- **Build Tool**: Vite

## Getting Started

### Prerequisites
- Node.js v20+
- npm

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/dhruv-git-sys/Hirelytics.git
   cd Hirelytics
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production
```sh
npm run build
npm run start
```

## Usage
1. **Sign In**: Log in to your puter account.
2. **Upload Resume**: Go to 'Upload Resume', fill in job details, and upload your PDF.
3. **Analyze**: The app converts your PDF to an image, stores it, and sends it for AI analysis.
4. **Review Feedback**: View ATS score, detailed feedback, and improvement tips.
5. **Track Submissions**: See all your resumes and their scores on the homepage.
6. **Wipe Data**: Optionally, clear all stored data from your account.

## Project Structure
- `app/` - Main application code (components, routes, libraries)
- `constants/` - Static data and feedback formats
- `public/` - Static assets (icons, images, PDF worker)
- `types/` - TypeScript type definitions
- `Dockerfile` - Container build instructions
- `vite.config.ts` - Vite configuration
- `package.json` - Project metadata and scripts

## Contributing
Pull requests and suggestions are welcome! Please open an issue to discuss changes before submitting PRs.

## License
MIT

---

**Hirelytics** helps you get smart, actionable feedback for your resume and boosts your chances of getting noticed by recruiters. Happy job hunting!
