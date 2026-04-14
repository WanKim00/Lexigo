# Lexigo

📖 Lexigo is a gamified dictionary web app that helps users look up and learn new words. Designed to be both functional and educational, Lexigo provides tools such as flashcards and quizzes to reinforce vocabulary learning. Users can log in, search for word definitions, and save their favorite words for later review.

## Screenshots
### Dashboard
<img width="700" alt="Screenshot 2026-04-14 at 5 34 07 PM" src="https://github.com/user-attachments/assets/cc976d4e-fef8-46d6-ada6-89e374c793ab" />

### Flashcards
<img width="700" alt="image" src="https://github.com/user-attachments/assets/00a6d654-ea21-49de-8507-d0881c184859" />

### Favorites
<img width="700" alt="image" src="https://github.com/user-attachments/assets/78ea7ef1-6aa8-4de3-9156-0291667c1904" />


## 🌐 Live Demo

Access the deployed app here:  
👉 [https://lexigo-61867.web.app](https://lexigo-61867.web.app)

## 🚀 Features

- 🔍 **Dictionary Search** – Instantly look up definitions, parts of speech, and pronunciation.
- ⭐ **Favorites List** – Save words you want to revisit later.
- 🧠 **Flashcards & Quizzes** – Practice and test your vocabulary knowledge.
- 🔐 **User Authentication** – Secure login with Firebase Authentication.
- 📅 **Word of the Day** – Daily vocabulary suggestions to expand your knowledge
  
## 🛠️ Tech Stack

- **Frontend**: React (Web)
- **Backend/Database**: Firebase (Authentication & Firestore)
- **Deployment**: Firebase Hosting
- **Package Manager**: npm

## 📦 Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/WanKim00/Lexigo.git
cd lexigo
npm install
npm start
```

The app should open on `http://localhost:3000/` in your browser.

## 🚚 Deployment

Lexigo is deployed using Firebase Hosting. To deploy a new version:

```bash
npm run build
firebase deploy
```

Ensure you have the Firebase CLI installed and are logged in to your Firebase account.

## 🗂️ Data Source

Lexigo uses the [Free Dictionary API](https://dictionaryapi.dev/) to fetch word definitions, phonetics, parts of speech, and example usage. All dictionary data shown in the app is retrieved from this open-source API.


## 📄 License

This project is licensed under the MIT License.

---

Made with 💡 by the Lexigo Team
