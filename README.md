# ♟️ Lichess Logic Bot
[![Python Version](https://img.shields.io/badge/python-3.13-blue.svg)](https://python.org)
[![Lichess Bot](https://img.shields.io/badge/Lichess-Bot--Profile-orange.svg)](https://lichess.org/@/Royal-Bot)
[![Engine](https://img.shields.io/badge/Engine-Stockfish-green.svg)](https://stockfishchess.org/)

An automated chess intelligence that leverages the **Lichess Bot API** and **Stockfish** engine to compete in real-time global matches.

## 🚀 How it Works
1. **The Listener:** Connects to the Lichess event stream using an asynchronous `ndjson` stream to detect new challenges and game starts.
2. **The Brain:** Upon opponent move detection, the current board state (FEN) is processed by the **Stockfish Engine** to determine the optimal move.
3. **The Execution:** Automatically transmits the calculated move back to the Lichess API with zero human intervention.

## 🏗️ Tech Stack
* **Python 3.13:** Asynchronous event-loop architecture.
* **Lichess API:** REST and Stream integration for bot account management.
* **Stockfish 16:** High-performance UCI engine for move calculation.

## 📉 Live Bot Status
You can challenge the bot or watch it play live here:
👉 **[Royal-Bot on Lichess](https://lichess.org/@/Royal-Bot)**

---
*Created by [King-of-javascript](https://github.com/King-of-javascript)*
