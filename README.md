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

---

## NPM Packages Used

The following NPM packages are used in the project:

1. **React Router DOM**: For routing and private route functionality.
   ```bash
   npm install react-router-dom
   ```
