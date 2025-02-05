## Assignment category : '003'

## Project Name : Lingo Bingo: A Vocabulary Learning Application

Lingo Bingo is a fun and interactive language learning application designed to help users expand their vocabulary and improve communication skills in a specific language. With a unique focus on vocabulary, this application makes the learning process easier, engaging, and accessible for users of all skill levels.

## Live URL : https://lingo-bingo-499c0.web.app/

## Purpose

The goal of Lingo Bingo is to simplify the vocabulary learning process for a specific language (e.g., Japanese, Spanish, etc.) while providing users with a feature-rich, user-friendly experience. By incorporating gamification, structured lessons, and audio pronunciations, users can immerse themselves in their target language and improve retention.

## Key Features

1. **Responsive Design**: Fully responsive interface, optimized for mobile, tablet, and desktop devices.
2. **User Authentication**: Secure login, registration, and social login (Google) using Firebase.
3. **Private Routes**: Access to lessons, tutorials, and user profiles restricted to authenticated users.
4. **Structured Learning**:
   - 10 lessons with categorized vocabulary cards.
   - Vocabulary JSON data includes word, pronunciation, meaning, part of speech, examples, and more.
5. **Interactive Features**:
   - "When to Say" modal with examples for each vocabulary word.
   - Text-to-speech functionality for vocabulary pronunciation.
6. **Tutorials**: Embedded YouTube videos to teach language basics like alphabets.
7. **Profile Management**:
   - View and update user profile (name and photo).
   - Functional "Forgot Password" feature for password recovery.
8. **Dynamic Home Page**:
   - Animated success counters for user engagement.
   - Extra sections to enrich the learning experience.
9. **Error Handling**: Custom 404 page with navigation to the home route.
10. **Secure Firebase Configuration**: Environment variables for Firebase API keys.
11. **Deployment**: Hosted on Netlify/Surge/Firebase with domain authorization.


### 3. Technologies Used
- React.js
- Firebase for authentication and backend
- MongoDB for storing user and lesson data
- Tailwind CSS for styling
- React Router DOM for page routing
- DaisyUI for UI components
- React Icons for icons
- Firebase Hosting (for deployment)


### 5. Dependencies Used
- react
- react-router-dom
- tailwindcss
- firebase
- react-icons
- react-countup
- aos
- daisyui
- react-slick (for carousels)
- react-speech-recognition (for pronunciation)
  
### 6. How to Run the Project Locally

#### Prerequisites:
- Node.js
- Firebase account
- MongoDB (optional for some features)

#### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/lingo-bingo.git
   cd lingo-bingo
   Install dependencies:

bash
Copy
Edit
npm install
Create a .env file in the root of the project and add your Firebase credentials:

plaintext
Copy
Edit
REACT_APP_FIREBASE_API_KEY=your-firebase-api-key
REACT_APP_FIREBASE_AUTH_DOMAIN=your-firebase-auth-domain
REACT_APP_FIREBASE_PROJECT_ID=your-firebase-project-id
REACT_APP_FIREBASE_STORAGE_BUCKET=your-firebase-storage-bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-firebase-sender-id
REACT_APP_FIREBASE_APP_ID=your-firebase-app-id
Start the application:

bash
Copy
Edit
npm start
Open the app in your browser

