# ♟️ ChessAnalyzer

**ChessAnalyzer** is a C# application that analyzes your chess games, finds your most common mistakes using Stockfish and gives you personalized feedback—all using Blazor UI.

---

## 🔧 Tech Stack

- C# (.NET 8)
- Blazor Server (frontend)
- PostgreSQL (database)
- Stockfish (chess engine)
- Entity Framework Core
- Clean Architecture + SOLID Principles

---

## 💡 Features

- Upload PGN files from Chess.com or Lichess
- Analyze games with Stockfish
- Detect blunders, mistakes, inaccuracies
- View evaluation graphs per game
- Find repeated mistake patterns (opening, middlegame, endgame)
- Clean, modern UI using Blazor

---

## 🧠 Why this project?

> “Most chess apps show you your blunders. This one helps you **understand them**.”

This is a portfolio-grade project made to demonstrate:
- Clean code architecture (DDD, DI, SOLID)
- Real-world application of C# + Blazor
- Multithreading, async pipelines, and chess AI analysis
- PostgreSQL usage with EF Core

---

## 🛠️ Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- [PostgreSQL](https://www.postgresql.org/) (or Docker)
- [Stockfish binary](https://stockfishchess.org/download/)

### Setup

```bash
git clone https://github.com/your-username/ChessAnalyzer.git
cd ChessAnalyzer

# Run DB migrations
dotnet ef database update --project ChessAnalyzer.Infrastructure

# Run the app
dotnet run --project ChessAnalyzer.Presentation
