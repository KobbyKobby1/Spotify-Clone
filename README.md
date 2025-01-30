# 🎵 Spotify Clone

A **Spotify Clone** built using modern web technologies, allowing users to browse, search, and play music with a sleek UI similar to Spotify. 

## 🚀 Features
- 🔍 Search for songs, artists, and albums
- 🎵 Play, pause, and control music playback
- 🎼 Browse trending music and curated playlists
- 🔗 Spotify API integration for real data
- 📱 Responsive design for mobile and desktop

## 📌 Tech Stack
- **Frontend:** React.js / Next.js
- **Backend:** Node.js / Express (if applicable)
- **Authentication:** Spotify OAuth
- **Styling:** Tailwind CSS / Styled Components
- **State Management:** Redux / Context API
- **Deployment:** Vercel / Netlify

## 🛠 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/KobbyKobby1/Spotify-Clone.git
cd Spotify-Clone
```

### 2️⃣ Install Dependencies
```sh
npm install  # OR yarn install
```

### 3️⃣ Setup Environment Variables
Create a `.env` file in the root directory and add:
```env
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
REDIRECT_URI=http://localhost:3000/callback
```
Obtain your **Client ID and Secret** from [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).

### 4️⃣ Run the App
#### For Web (React/Next.js)
```sh
npm run dev  # OR yarn dev
```
Visit `http://localhost:3000` to access the app.

#### For React Native (Expo)
```sh
expo start
```
Scan the QR code with the **Expo Go** app on your mobile device.

## 📸 Screenshots
[Screenshot 2025-01-30 023015](https://github.com/user-attachments/assets/b7cee62a-67e6-45f9-a4cc-cd29ebc99d5f)

## 🚀 Deployment
If using **Vercel**, deploy with:
```sh
vercel
```
If using **Netlify**, deploy with:
```sh
netlify deploy
```

## 📜 License
This project is licensed under the **MIT License**.

---
### 📩 Contributing
Feel free to fork this repository and submit pull requests! Contributions are welcome. 💙
