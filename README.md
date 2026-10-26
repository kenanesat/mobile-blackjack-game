# ♠️ Android Blackjack Game Application

This repository contains the mobile Blackjack (21) card game application developed for the **CPR 210 Mobile Application Development** course at **Çankaya University (Computer Programming Department)**.

---

## 🛠️ Technologies & Tools Used
* **Language:** Kotlin
* **IDE:** Android Studio
* **UI Framework:** Jetpack Compose (Material 3)
* **State Management:** `remember` and `mutableStateOf`
* **Logic:** Custom 52-card Deck management, Ace dynamic value calculation (1 or 11), automatic Dealer AI.

---

## 🎮 Key Features & Game Logic
* **Declarative UI:** Built entirely using Jetpack Compose without XML layouts.
* **Game States:** Implements structured states (`READY`, `PLAYER_TURN`, `FINISHED`) to handle UI recomposition.
* **Dealer Rules:** The dealer's second card is hidden during the player's turn and automatically draws cards until reaching a minimum score of 17.
* **Deck Management:** Standard 52-card deck with dynamic reshuffling.

---

## 📑 Project Report & Presentation
The complete PDF project documentation (`kenanesatsen202246031projectreport.pdf`), presentation slides (`kenanesatsen202246031slide.pdf`), and full source code (`blackjack.zip`) are available in this repository.

* **Author:** Kenan Esat Şen
* **University:** Çankaya University (Computer Programming)
* **Instructor:** Lect. Efe Çiftci
* **Date:** 31.12.2025
