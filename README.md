<div align="center">

<img src="assets/icon.svg" alt="University Archive" width="128" height="128">

# University Archive

**28 projects, labs and coursework from university and my internship, made by Akulav.**

Bootloaders and lexers, search and game AI, encrypted UDP, Elixir stream processing, microservices, WebGL and data
analysis: the path from a first C program to distributed systems.

![Projects](https://img.shields.io/badge/projects-28-7c5cff?style=for-the-badge)
![Languages](https://img.shields.io/badge/languages-8-1e3a8a?style=for-the-badge)
![Status](https://img.shields.io/badge/status-archived-5c6270?style=for-the-badge)

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Assembly](https://img.shields.io/badge/x86%20Assembly-6E4C13?style=flat-square&logo=intel&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)

[Highlights](#-highlights) ·
[All projects](#-all-projects) ·
[Running them](#-running-them)

</div>

---

> [!NOTE]
> Kept for the record, not maintained. Many of these were written early in my studies: expect rough edges, hard-coded
> values and outdated dependencies. Every folder is self-contained and has its own README with what it does and how
> to run it.

## ⭐ Highlights

<table>
<tr>
<td width="50%" valign="top">

### 🖥️ [basic_x86_assembler](basic_x86_assembler)
A 16-bit **bootloader and tiny kernel** with a shell-like prompt and a drawing mode, plus a **lexer for a toy language**
written entirely in x86 assembly.

</td>
<td width="50%" valign="top">

### 🍸 [safe_udp](safe_udp): the "Vodka Protocol"
UDP made reliable: error checking, retransmission, **Diffie-Hellman-style key agreement**, encryption and lossless
compression, in two calls: send and receive.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☁️ [cloud-service](cloud-service)
A **microservice system** in C#: gateway, login, data, cache and database services talking over TCP, each in its own
**Docker** container.

</td>
<td width="50%" valign="top">

### 💧 [RTP-LAB1 → 3](RTP-LAB1)
**Elixir** stream processing in three steps: supervised workers scoring tweet sentiment, batched persistence to
**MongoDB**, then a TCP **message broker** with clients.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧩 [Puzzle15](Puzzle15) · [TicTacToeAI](TicTacToeAI)
A 15-puzzle solved with **Best-First, BFS and DFS**, and a tic-tac-toe opponent that never loses (**Minimax**).

</td>
<td width="50%" valign="top">

### 🛡️ [VulnerabilityScanner](VulnerabilityScanner)
Audits Windows against official **CIS benchmark** `.audit` files: load, edit and save policies, scan, export reports.

</td>
</tr>
</table>

## 📚 All projects

### 🧮 Algorithms & data structures

| Project | Language | What it is |
| :-- | :-- | :-- |
| [AutomaticRootFinder](AutomaticRootFinder) | Java | Bisection root finder that locates its own search bounds |
| [BinaryTreeOperations](BinaryTreeOperations) | C | Binary search tree: insert, delete, search, traversals, ASCII printing |
| [MultithreadedMergeSorting](MultithreadedMergeSorting) | C | Merge sort split across a configurable number of POSIX threads |
| [PiCruncher](PiCruncher) | C# | WinForms app that computes digits of Pi |
| [Polygon-Triangulation](Polygon-Triangulation) | C# | Click to draw a polygon and watch it get triangulated |
| [Puzzle15](Puzzle15) | C# | 15-puzzle solver using Best-First, BFS and DFS search |
| [Next-Random-Number-Interpolation](Next-Random-Number-Interpolation) | C | My first program: predicts the next value from a seeded RNG |

### 🔤 Formal languages & low level

| Project | Language | What it is |
| :-- | :-- | :-- |
| [ConvertToChomsky](ConvertToChomsky) | Java | Converts a context-free grammar to Chomsky Normal Form |
| [basic_x86_assembler](basic_x86_assembler) | x86 ASM | Bootloader, tiny kernel/shell and a lexer for a toy language |

### 🎮 Games & AI

| Project | Language | What it is |
| :-- | :-- | :-- |
| [BullsAndCows](BullsAndCows) | C# | The computer guesses your secret number in Bulls & Cows |
| [TicTacToeAI](TicTacToeAI) | C# | Tic-tac-toe against an unbeatable Minimax opponent |
| [GnomeVisualNovel](GnomeVisualNovel) | Unity / C# | Short visual novel about a gnome rescuing his brother |
| [LifeSimulation](LifeSimulation) | Unity / C# | Grid-based life simulation, with a prebuilt Linux binary |
| [ClockTestPilot](ClockTestPilot) | C# | Timed visual-memory test for reading clock faces |

### 🔐 Security & utilities

| Project | Language | What it is |
| :-- | :-- | :-- |
| [OfflinePasswordManager](OfflinePasswordManager) | C# | The original SeePass: a fully offline, encrypted password manager (today rewritten in Rust as [SeePass](https://github.com/Akulav/offline-password-manager)) |
| [PasswordGenerator](PasswordGenerator) | C# | Simple random password generator |
| [VulnerabilityScanner](VulnerabilityScanner) | C# | Audits Windows against CIS benchmark `.audit` files |

### 🌐 Networking & distributed systems

| Project | Language | What it is |
| :-- | :-- | :-- |
| [safe_udp](safe_udp) | C# | "Vodka Protocol": reliable, encrypted, compressed UDP |
| [cloud-service](cloud-service) | C# / Docker | Microservices: gateway, login, data, cache, database |
| [PR-LAB-1](PR-LAB-1) | C# | Multithreaded crawler that normalises JSON/XML/YAML/CSV and serves it over TCP |
| [RTP-LAB1](RTP-LAB1) | Elixir | Supervised worker pool doing sentiment analysis on a tweet stream |
| [RTP-LAB2](RTP-LAB2) | Elixir | RTP-LAB1 plus batched persistence to MongoDB |
| [RTP-LAB3](RTP-LAB3) | Elixir | RTP-LAB2 plus a TCP message broker and client |

### 🎨 Graphics

| Project | Language | What it is |
| :-- | :-- | :-- |
| [WebGL_Light](WebGL_Light) | JavaScript | Interactive WebGL shapes with a movable, coloured light |
| [WebGL_TexturesAndModels](WebGL_TexturesAndModels) | JavaScript | Adds multiple lights, textures and model loading |

### 📊 Data analysis

| Project | Language | What it is |
| :-- | :-- | :-- |
| [AED_LAB1](AED_LAB1) | Python | Exploratory analysis and linear regression on housing data |
| [AED2](AED2) | Python | Exploratory analysis and a probit model on labour data |
| [DataAnalysisLabs](DataAnalysisLabs) | Python | Dimensionality reduction experiments: PCA, LLE, MDS, t-SNE |

## 🚀 Running them

Each folder's README has the exact steps. In general:

| Kind | You need | How |
| :-- | :-- | :-- |
| **C#** (WinForms, console) | Visual Studio with the *.NET desktop development* workload | Open the `.sln`, press **Start** |
| **C** | `gcc` (pthreads for the multithreaded ones) | `gcc main.c -o app -pthread && ./app` |
| **Java** | JDK 8 or newer | `javac Main.java && java Main` |
| **Elixir** | Elixir and Mix | `mix deps.get && mix run --no-halt` |
| **Python** | Python 3 with `pandas numpy matplotlib seaborn scikit-learn statsmodels` | `python <file>.py` |
| **JavaScript** (WebGL) | A browser with WebGL | Open the folder's `.html` page (or serve the folder) |
| **x86 assembly** | NASM and QEMU | Run the `FULL` script: it builds a floppy image and boots it in QEMU |
| **Unity** | Unity 2019.3.x | Open the folder in Unity Hub; `Library/` is rebuilt on first open |

---

<div align="center">

**Made with ❤️ by [Akulav](https://github.com/Akulav)** (Turcan Catalin)

<sub>© 2026 Akulav. Source-available under the <a href="LICENSE">Akulav Source-Available License</a>.</sub>

</div>
