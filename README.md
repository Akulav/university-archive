# University Archive

An archive of projects, labs and coursework I built during university and my internship.
Each folder is a self-contained project with its own README covering what it does and how to run it.

> These projects are kept for archival purposes. Many were written early in my studies and are
> not maintained, so expect rough edges, hard-coded values and outdated dependencies.

## Projects

### Algorithms & Data Structures

| Project | Language | Description |
| --- | --- | --- |
| [AutomaticRootFinder](AutomaticRootFinder) | Java | Bisection root finder that locates its own search bounds |
| [BinaryTreeOperations](BinaryTreeOperations) | C | Binary tree insert, delete, search, traversals and ASCII printing |
| [MultithreadedMergeSorting](MultithreadedMergeSorting) | C | Merge sort split across a configurable number of threads |
| [PiCruncher](PiCruncher) | C# | WinForms app that computes digits of Pi |
| [Polygon-Triangulation](Polygon-Triangulation) | C# | Click to draw a polygon and watch it get triangulated |
| [Puzzle15](Puzzle15) | C# | 15-puzzle solver using Best-First, BFS and DFS search |
| [Next-Random-Number-Interpolation](Next-Random-Number-Interpolation) | C | My first program: predicts the next value from a seeded RNG |

### Formal Languages & Low-Level

| Project | Language | Description |
| --- | --- | --- |
| [ConvertToChomsky](ConvertToChomsky) | Java | Converts a context-free grammar to Chomsky Normal Form |
| [basic_x86_assembler](basic_x86_assembler) | x86 ASM | Bootloader, tiny kernel/shell and a lexer for a toy language |

### Games & AI

| Project | Language | Description |
| --- | --- | --- |
| [BullsAndCows](BullsAndCows) | C# | Computer guesses your secret number in Bulls & Cows |
| [TicTacToeAI](TicTacToeAI) | C# | Tic-tac-toe against an unbeatable Minimax opponent |
| [GnomeVisualNovel](GnomeVisualNovel) | Unity / C# | Short visual novel about a gnome rescuing his brother |
| [LifeSimulation](LifeSimulation) | Unity / C# | Grid-based life simulation with a prebuilt Linux binary |
| [ClockTestPilot](ClockTestPilot) | C# | Timed visual-memory test for reading clock faces |

### Security & Utilities

| Project | Language | Description |
| --- | --- | --- |
| [OfflinePasswordManager](OfflinePasswordManager) | C# | SeePass: fully offline, encrypted password manager |
| [PasswordGenerator](PasswordGenerator) | C# | Simple random password generator |
| [VulnerabilityScanner](VulnerabilityScanner) | C# | Audits Windows against CIS benchmark `.audit` files |

### Networking & Distributed Systems

| Project | Language | Description |
| --- | --- | --- |
| [safe_udp](safe_udp) | C# | "Vodka Protocol": reliable, encrypted, compressed UDP |
| [cloud-service](cloud-service) | C# / Docker | Microservice system: gateway, login, data, cache, DB |
| [PR-LAB-1](PR-LAB-1) | C# | Multithreaded crawler that normalises JSON/XML/YAML/CSV and serves it over TCP |
| [RTP-LAB1](RTP-LAB1) | Elixir | Supervised worker pool doing sentiment analysis on a tweet stream |
| [RTP-LAB2](RTP-LAB2) | Elixir | RTP-LAB1 plus batched persistence to MongoDB |
| [RTP-LAB3](RTP-LAB3) | Elixir | RTP-LAB2 plus a TCP message broker and client |

### Graphics

| Project | Language | Description |
| --- | --- | --- |
| [WebGL_Light](WebGL_Light) | JavaScript | Interactive WebGL shapes with a movable, coloured light |
| [WebGL_TexturesAndModels](WebGL_TexturesAndModels) | JavaScript | Adds multiple lights, textures and model loading |

### Data Analysis

| Project | Language | Description |
| --- | --- | --- |
| [AED_LAB1](AED_LAB1) | Python | Exploratory analysis and linear regression on housing data |
| [AED2](AED2) | Python | Exploratory analysis and probit model on labour data |
| [DataAnalysisLabs](DataAnalysisLabs) | Python | Dimensionality reduction (PCA, LLE, MDS, t-SNE) experiments |

## Common requirements

- **C# projects**: Visual Studio with the .NET Framework desktop workload. Open the `.sln` file and press Start.
- **C projects**: any C compiler (`gcc`). Multithreaded ones need pthreads.
- **Java projects**: JDK 8 or newer.
- **Elixir projects**: Elixir and Mix.
- **Python projects**: Python 3 with `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`.
- **Unity projects**: Unity 2019.3.x. The `Library/` folder is regenerated when the project is opened.

## Author

Turcan Catalin ([@Akulav](https://github.com/Akulav))
