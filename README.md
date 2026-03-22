# 🕹️ Video Game Tracker

A full-stack web app to track your video game collection. Users can **add, delete, search, and filter games** by status (Played/Unplayed) and track details like company, description, and date added — all using **Vanilla JavaScript, Node.js, and Express**.

---

## ⚡ Features

* ➕ Add new games with **Title**, **Company**, and **Description**
* 🟢/🔴 Track if games are **Played** or **Unplayed**
* ❌ Delete games from your collection
* 🔍 Search for games by title or company
* 📅 Automatically adds a **timestamp** when games are added

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, Vanilla JS
* **Backend:** Node.js, Express
* **Data Storage:** JSON file (`games.json`)
* **Communication:** RESTful API using `fetch()`

---

## 🚀 Getting Started

These instructions are for users who **download the ZIP from GitHub** using the green Code button.

1. **Download the project**

   * Click the **Code → Download ZIP** button on GitHub.
   * Unzip the downloaded folder.

2. **Install Node.js and npm** (if not installed):

Windows/macOS: Download and install Node.js (LTS version) from [https://nodejs.org/](https://nodejs.org/). This also installs npm.
Linux (Ubuntu/Debian):

     ```bash
     sudo apt update
     sudo apt install nodejs npm
     ```

3. **Open the project folder in Visual Studio Code** (or any terminal).

4. **Install project dependencies**

```bash
npm install
```

5. **Start the server**

```bash
npm run start
```

6. **Open in your browser**

```text
Go to http://localhost:5000
```

> The server must be running on your own machine to access `localhost`. This is not a public link.

---

## 💡 Notes

* Make sure the games.json file is writable, or the app won’t save new games.
* Optional: Track **ratings** or **platforms** by adding fields in the JSON and frontend.
* Optional: Use **Postman** to test API routes.
