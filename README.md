# Sign to Text & Speech to Sign Web Application 🤟💬

A full-stack Node.js and client-side JavaScript web application that provides bi-directional translation between American Sign Language (ASL) and text/speech.

---

## 📌 Features

* **Sign to Text Translation**: Real-time camera feed processing that translates ASL hand gestures into written text.
* **Speech to Sign Translation**: Audio input and speech recognition rendered into ASL gesture visualizations/animations.
* **User Authentication**: User registration and login functionality.
* **Real-Time Interactive Chat**: Real-time messaging and sign language avatar/display integration.
* **Visual Waveform Display**: Dynamic audio waveform visualization for audio input streams.

---

## 🛠️ Tech Stack

* **Backend**: Node.js, Express.js (`server.js`)
* **Frontend**: HTML5, CSS3, JavaScript (ES6+)
* **Machine Learning / Computer Vision**: Client-side ASL classification and landmark modeling (`asl-classifier.js`, `asl-model.js`)
* **Dependencies**: Configured via `package.json`

---

## 🚀 Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/) (v14.x or higher)
* npm (Node Package Manager)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/sign-to-text.git
cd sign-to-text-main

```


2. **Install dependencies:**
```bash
npm install

```


3. **Start the application:**
```bash
npm start

```


*Alternatively, run `node server.js` directly.*
4. **Access the web app:**
Open your browser and navigate to `http://localhost:3000` (or your configured port).

---

## 📂 Project Structure

```
sign-to-text-main/
├── public/
│   ├── css/
│   │   └── styles.css          # Main UI stylesheet
│   ├── js/
│   │   ├── app.js              # Application entry point
│   │   ├── asl-classifier.js   # ASL gesture classification logic
│   │   ├── asl-display.js     # ASL visual rendering component
│   │   ├── asl-model.js        # Model pipeline and inference helper
│   │   ├── auth.js             # Client-side session management
│   │   ├── chat.js             # Real-time chat & message processing
│   │   ├── login.js            # Login handling logic
│   │   ├── register.js         # User registration handling
│   │   ├── sign-to-text.js     # Video input processing & gesture extraction
│   │   ├── speech-to-sign.js   # Speech recognition & sign animation mapping
│   │   └── waveform.js         # Audio visualization handler
│   ├── index.html              # Main application dashboard
│   ├── login.html              # Authentication login view
│   └── register.html           # User signup view
├── package.json                # Project dependencies & scripts
├── package-lock.json           # Dependency lockfile
├── server.js                   # Express server entry point
└── README.md                   # Project documentation

```

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for details.
