# SmartWise: AI-Based Interview Preparation Platform

SmartWise is a cutting-edge AI-powered web application designed to help users prepare for job interviews efficiently. With features like customizable interview settings, AI-generated questions, real-time transcripts, and detailed feedback, SmartWise provides a comprehensive and personalized interview experience.

## Features

### 1. **User Authentication and Security**
- Firebase is used for secure user authentication.
- User credentials (name, email, and password) are hashed for robust security.

### 2. **Interview Customization**
- Users specify the following:
  - **Role** of the interview.
  - **Tech stack** (e.g., Python, JavaScript, etc.).
  - **Interview type**: Technical, behavioral, or mixed.
  - **Interview level**: Junior, senior, or fresher.
  - **Number of questions** for the interview.

### 3. **AI-Powered Interaction**
- VAPI-powered AI Assistant interacts with the user to collect interview details.
- Google AI SDK generates tailored interview questions based on the user's input.
- Questions and user responses are stored in Firebase for future reference.

### 4. **Dashboard**
- Displays a list of created interview cards.
- Users can start interviews directly from the dashboard.

### 5. **Feedback System**
- AI evaluates the user's responses using Google Gemini.
- Generates a detailed feedback page including:
  - Total score.
  - Strengths.
  - Areas for improvement.
- Feedback is stored and displayed for review.

### 6. **Transcript Management**
- Real-time transcripts of interactions between the user and AI are stored.
- Users can review their interview responses and AI feedback.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Firebase, Google AI SDK, VAPI
- **Hosting**: Vercel
- **Version Control**: GitHub

## Deployment
PrepWise is hosted on Vercel. Check it out here: [PrepWise Live](https://ai-mock-interviews-rouge.vercel.app/)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/prepwise.git
   ```

2. Navigate to the project directory:
   ```bash
   cd prepwise
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up Firebase:
   - Configure Firebase authentication and Firestore database.
   - Update the Firebase configuration in the `.env` file.

5. Start the development server:
   ```bash
   npm run dev
   ```

6. Access the app at `http://localhost:3000`.

## How It Works

1. **Start a New Interview**:
   - Specify the role, tech stack, type, level, and number of questions.
   - AI generates questions and stores them in Firebase.

2. **Take the Interview**:
   - Users answer questions directly on the platform.
   - AI evaluates responses and generates detailed feedback.

3. **Review Feedback**:
   - View scores and areas for improvement on the feedback page.
   - Reattempt interviews to track progress.



## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.


---

### Acknowledgments
- Firebase for authentication and data storage.
- VAPI for powering the AI Assistant.
- Google AI SDK for generating interview questions and feedback.
- Vercel for seamless deployment.

---


