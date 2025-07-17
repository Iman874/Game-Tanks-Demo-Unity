# 🕹️ Game Tanks Demo Unity

[Baca dalam Bahasa Indonesia](#bahasa-indonesia) | [Read in English](#english)

---

## POIN-POIN MATERI

* 📜 [Deskripsi Singkat](#deskripsi-singkat)
* 🧰 [Struktur Proyek](#struktur-proyek)
* ⚙️ [Teknologi & Arsitektur](#teknologi--arsitektur)
* 📆 [Komponen Inti](#komponen-inti)
* ⚖️ [Cara Instalasi](#cara-instalasi)

---

<a name="bahasa-indonesia"></a>

## 🇮🇩 Bahasa Indonesia

<a name="deskripsi-singkat"></a>

### 📜 Deskripsi Singkat

**Game Tanks Demo Unity** adalah sebuah project demo game tank berbasis Unity yang menampilkan gameplay multiplayer sederhana. Game ini dirancang untuk memudahkan pembelajaran tentang pengembangan game tank, sistem kontrol player, AI musuh, serta efek visual dan audio di Unity.

Fitur utama:
* Multiplayer lokal (split screen)
* Kontrol tank (movement, shoot, health)
* Musuh AI sederhana
* Efek ledakan dan suara
* UI skor dan game over

---

<a name="struktur-proyek"></a>

### 🧰 Struktur Proyek

```
📁 Assets/                  → Semua file Unity assets
📁 Assets/Scripts/          → Script C# untuk gameplay
📁 Assets/Prefabs/          → Prefabs tank, peluru, ledakan
📁 Assets/Scenes/           → Scene utama game
📁 Assets/Materials/        → Material dan shader
📁 Assets/UI/               → UI Canvas, Score, Menu
```

---

<a name="teknologi--arsitektur"></a>

### ⚙️ Teknologi & Arsitektur

* **Engine:** Unity 2022 atau terbaru
* **Bahasa:** C#
* **UI:** Unity Canvas & TextMeshPro
* **Multiplayer:** Local split screen
* **AI:** Simple waypoint & patrol
* **Audio:** Unity AudioSource
* **Arsitektur:** Komponen script modular (PlayerController, EnemyAI, Bullet, GameManager)

---

<a name="komponen-inti"></a>

### 📆 Komponen Inti

* **Kontrol Tank:** `PlayerController.cs`, `TankMovement.cs`
* **AI Musuh:** `EnemyAI.cs`
* **Gameplay Manager:** `GameManager.cs`
* **Peluru & Ledakan:** `Bullet.cs`, `Explosion.cs`
* **UI:** `ScoreUI.cs`, `GameOverUI.cs`

---

<a name="cara-instalasi"></a>

### ⚖️ Cara Instalasi

1. **Clone repositori:**

```bash
git clone https://github.com/Iman874/Game-Tanks-Demo-Unity.git
```

2. **Buka di Unity Hub**

* Pilih "Open Project" dan arahkan ke folder hasil clone

3. **Build & Jalankan:**

* Pilih scene utama di folder `Assets/Scenes/`
* Tekan Play untuk mencoba game
* Build ke platform yang diinginkan (Windows, Mac, Android, dll)

---

<a name="english"></a>

## 🇬🇧 English

<a name="deskripsi-singkat"></a>

### 📜 Overview

**Game Tanks Demo Unity** is a Unity-based demo project showcasing simple multiplayer tank gameplay. It is designed as a learning resource for tank game development, including player controls, enemy AI, and visual/audio effects in Unity.

Key features:
* Local multiplayer (split screen)
* Tank controls (move, shoot, health)
* Simple enemy AI
* Explosion effects and sounds
* Score & Game Over UI

---

<a name="struktur-proyek"></a>

### 🧰 Project Structure

```
📁 Assets/                  → All Unity assets
📁 Assets/Scripts/          → C# gameplay scripts
📁 Assets/Prefabs/          → Tank, bullet, explosion prefabs
📁 Assets/Scenes/           → Main game scenes
📁 Assets/Materials/        → Materials and shaders
📁 Assets/UI/               → UI Canvas, Score, Menu
```

---

<a name="teknologi--arsitektur"></a>

### ⚙️ Tech Stack & Architecture

* **Engine:** Unity 2022 or newer
* **Language:** C#
* **UI:** Unity Canvas & TextMeshPro
* **Multiplayer:** Local split screen
* **AI:** Simple waypoint & patrol
* **Audio:** Unity AudioSource
* **Architecture:** Modular scripts (PlayerController, EnemyAI, Bullet, GameManager)

---

<a name="komponen-inti"></a>

### 📆 Core Components

* **Tank Controls:** `PlayerController.cs`, `TankMovement.cs`
* **Enemy AI:** `EnemyAI.cs`
* **Gameplay Manager:** `GameManager.cs`
* **Bullet & Explosion:** `Bullet.cs`, `Explosion.cs`
* **UI:** `ScoreUI.cs`, `GameOverUI.cs`

---

<a name="cara-instalasi"></a>

### ⚖️ Setup and Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Iman874/Game-Tanks-Demo-Unity.git
```

2. **Open in Unity Hub**

* Select "Open Project" and navigate to the cloned folder

3. **Build & Run:**

* Open the main scene in `Assets/Scenes/`
* Press Play to try the game
* Build to your desired platform (Windows, Mac, Android, etc)

---

> 🌟 Developed as a demo project for learning Unity tank game development – 2024
