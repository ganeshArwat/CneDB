# 🎬 CneDB – Movie Search & Watchlist App

CneDB is a React-based web application that allows users to search for movies using the [OMDb API](http://www.omdbapi.com/), view their details, and add them to a personal watchlist. The watchlist is saved in the browser’s local storage, so it stays intact even after a page refresh.

---

## 🔍 Features

- 🔎 **Search Movies** – Type in any movie name to get results from OMDb.
- 📝 **View Movie Info** – Get essential details like title, year, and poster.
- ⭐ **Add to Watchlist** – Save your favorite movies for later.
- ♻️ **Persistent Storage** – Watchlist is saved using `localStorage`.
- ⚡ **Instant Feedback** – Real-time updates to the watchlist UI.

---

## 🚀 Tech Stack

- **React.js** – Component-based frontend library
- **OMDb API** – Third-party movie database API
- **LocalStorage** – Client-side persistence

---

## 📸 Screenshots

## ![Demo Image](https://github.com/user-attachments/assets/615dc043-3cf6-46f4-8f7b-ffd12a0a273a)

## 🛠️ Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ganeshArwat/CneDB.git
   cd CneDB
   ```


2. Install dependencies:

   ```bash
   npm install
   ```

3. Get an API key from [OMDb API](http://www.omdbapi.com/apikey.aspx) (it's free)

4. Create a `.env` file in the root directory and add your API key:

   ```env
   REACT_APP_OMDB_API_KEY=your_api_key_here
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```

---
