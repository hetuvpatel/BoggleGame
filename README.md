# 🎲 Boggle Game — Elixir Edition

Welcome to the **Boggle Game** project — a fast, fun, and dynamic word-search game built entirely in **Elixir**! 🚀  
Sharpen your mind and hunt for words across randomized Boggle boards, all powered by a robust and efficient functional programming backend.

---

## 📚 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [How to Play](#-how-to-play)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [How to Run](#-how-to-run)
- [Future Improvements](#-future-improvements)
- [Contact](#-contact)

---

## 🧩 About the Project

This Boggle Game implements:
- 🧠 **Dynamic Boggle board generation** (randomized 4x4 grid)
- 📜 **Word validation** from large English word lists
- 🧠 **Recursive search algorithms** to find valid words
- ⚡ **Optimized search** with depth-first search and backtracking
- 🧹 **Lightweight functional design** using Elixir's powerful recursion and pattern matching

Built as part of learning **functional programming**, this project demonstrates efficient **state handling**, **concurrent thinking**, and **pure functions**.

---

## ✨ Features

- 🔀 Random Boggle board generation every time!
- 🔎 Validates user input against a real dictionary (Scrabble official word lists and more).
- 🧠 Advanced search logic using **Depth-First Search (DFS)** with backtracking.
- 💾 Supports multiple word lists: `500`, `1000`, `3000`, `Scrabble 2006`, and `Scrabble 2019`.
- 🚀 Designed for **speed** and **scalability** — ready for real-time multiplayer versions in the future!

---

## 🎮 How to Play

1. The system generates a random **4x4 Boggle board**.
2. You can enter words you find by connecting adjacent letters horizontally, vertically, or diagonally.
3. Each word must exist in the loaded dictionary and obey Boggle movement rules.
4. The longer the word, the higher your score!

---

## 🛠️ Tech Stack

| Technology | Purpose |
|:-----------|:--------|
| **Elixir** | Functional backend programming |
| **Mix** | Build and dependency management |
| **ExUnit** | Automated testing |
| **Word Lists** | Dictionary validation and scoring |

---

## 🗂️ Project Structure

| File / Folder            | Purpose |
|:--------------------------|:--------|
| `boggle.ex`               | Core game logic (board generation, word finding) |
| `boggle_test.exs`         | Unit tests for game functionalities |
| `mix.exs`                 | Project configuration file |
| `test_helper.exs`         | Test runner setup |
| `word_list_*.txt`         | Word dictionaries (500, 1000, 3000 words, Scrabble official lists) |

---

## 🚀 How to Run

Clone the repository:
```bash
git clone https://github.com/hetuvpatel/BoggleGame.git
cd BoggleGame
```

Install Depend:
```bash
mix deps.get
```
Compile and run the Boggle game:
```bash
iex -S mix
```
Inside the `iex` shell, you can start playing with:
```bash
board = Boggle.generate_board()
Boggle.find_all_words(board, word_list)
```
Run test:
```bash
mix test
```
## 🔮 Future Improvements

- 🧠 **Add a graphical interface (GUI):** Create a visual Boggle board using Phoenix LiveView! 🔥
- 🌎 **Implement Multiplayer Mode:** Allow real-time multiplayer via distributed Elixir nodes.
- 📈 **Add scoring systems and leaderboards:** Track user performance and high scores.
- 🎙️ **Include voice recognition:** Enable players to input words by speaking!
- 🤖 **Train an AI:** Build an optimal Boggle solver that finds the best possible word combinations.

---

## 📬 Contact

- **Hetu Patel**
- 📫 [hetu.patel@torontomu.ca](mailto:hetu.patel@torontomu.ca)
- 🌐 [Portfolio Website](https://hetuvpatel.github.io/hetu-patel-portfolio/)
- 💻 [GitHub Profile](https://github.com/Patel-Hetu)

---

> _"Finding the right words has never been more fun!"_ 🎯🎲
