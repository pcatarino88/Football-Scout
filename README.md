# ⚽ Football-Scout

**Football-Scout** is a data-driven tool designed to analyze and compare football players from various European leagues using [FBREF](https://fbref.com/en/) as the primary data source.

---

## 📊 Overview

This project gathers and consolidates detailed stats from players across multiple leagues and seasons. It allows for:

- 📥 Automated scraping and cleaning of player statistics.
- 📈 Performance comparison based on customizable parameters and weights.
- 🔍 Search for the most similar players to a given *target player* (striker by default).
- 💰 Estimation of player market values using data scraped from [Transfermarkt](https://www.transfermarkt.pt/).

---

## 🛠️ Features

- **Player Similarity Finder**: Compares players based on position, metrics and weights defined by the user.
- **Custom Weighting System**: Personalize how important each stat is in the similarity comparison.
- **Market Value Estimation**: Automatically fetches market values from Transfermarkt for selected players.
- **Position Flexibility**: Though optimized for strikers, the tool can be extended to other positions.

---

## 📁 Project Structure

```bash
📦 Football-Scout/
├── Scout_Players.ipynb     # Main notebook: scraping, cleaning, similarity analysis
├── README.md               # Project documentation
