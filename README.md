# 🎵 Music Playlist Management System

A modular C++ console application for managing music playlists with features such as authentication, playlist CRUD, sorting, searching, and global playlist management.

---

# 📁 Project Structure

```txt
music_playlist/
│
├── src/
│   ├── main.cpp
│   ├── ui.cpp
│   ├── data.cpp
│   ├── auth.cpp
│   ├── crud.cpp
│   ├── sort.cpp
│   ├── search.cpp
│   ├── pages.cpp
│   └── globals.cpp
│
├── include/
│   ├── types.h
│   ├── globals.h
│   ├── ui.h
│   ├── data.h
│   ├── auth.h
│   ├── crud.h
│   ├── sort.h
│   ├── search.h
│   └── pages.h
│
├── data/
│   └── data_global.txt
│   └── data_playlists.txt
│   └── data_users.txt
|
└── README.md
```

---

# ✨ Features

- 🔐 User Authentication (Login & Register)
- 🎶 Playlist Management
- 🌍 Global Playlist System
- 🔎 Searching Algorithms
- 📊 Sorting Algorithms
- 💾 File Data Persistence
- 🖥️ Console UI Components

---

# ⚙️ Requirements

Before running the project, make sure you have:

- C++17 or newer
- GCC / MinGW Compiler
- VS Code or Terminal

---

# 🚀 How To Run The Program

## 📌 Step 1 — Open Terminal

Open terminal inside the project root folder:

```txt
music_playlist/
```

---

## 📌 Step 2 — Compile The Program

Run this command:

```bash
g++ src/main.cpp src/ui.cpp src/data.cpp src/auth.cpp src/crud.cpp src/sort.cpp src/search.cpp src/pages.cpp src/globals.cpp -std=c++17 -Wall -o app
```

If compilation succeeds, an executable file named `app.exe` will be created.

---

## 📌 Step 3 — Run The Program

### ▶️ PowerShell

```powershell
.\app
```

### ▶️ CMD

```cmd
app.exe
```

---

# 🛠️ Technologies Used

- C++
- Modular Programming
- File Handling
- Struct-Based Data Management
- Sorting Algorithms
- Searching Algorithms

---

# 📌 Notes

- The project uses a modular folder structure (`src/` and `include/`).
- Data is stored locally inside the `data/` folder.
- Built using standard C++17.

---

# 👨‍💻 Author
1. Andi Muhammad Alarice Haekal (Leader Project) 
2. Hammam Syamil 
3. Doni Julianto
   
Made with C++ and determination.
