# Java-Projects
Welcome! This folder contains all my Java projects. Below are brief descriptions and links to the corresponding project folders.

### List of projects

1. [JavaTextEditor](#JavaTextEditor)
2. [PharmacyAccountingApp](#PharmacyAccountingApp)
3. [Tic-Tac-Toe](#TicTacToe)
4. [Snake](#Snake)
5. [ATM App](#ATMApp)
6. [Currency Converter](#CurrencyConverter)
7. [Conway’s Game of Life](#ConwaysGameofLife)

## 1) JavaTextEditor
<div id="JavaTextEditor"></div>
<img width="871" height="637" alt="395850886-42b95c76-f5db-4148-ba99-82f62f1c1e19" src="https://github.com/user-attachments/assets/0d784248-0649-46e7-98f3-fbb45ebbe106" />

A desktop **rich-text editor** built with Swing. Create, edit, and format documents; open/save/export; insert images; and apply fonts, sizes, bold/italic styles via a menu-driven UI. Demonstrates `JTextPane` + `StyledDocument`, file I/O, and practical text manipulation.

**Key Features**
- File operations: open, save, export to **TXT / Markdown (.md) / HTML (.html)**
- Text formatting: font family (e.g., Arial, Times New Roman), size **4–128**, bold, italic
- Image insertion from local files
- Rich-text editing via **JTextPane** with real-time updates
- Menu-based UX: File / Edit / Format

**Technical Details**
- Java (JDK 8+)
- `javax.swing`, `javax.swing.text`, `java.awt`, `java.io`

<a href="https://github.com/NicolasPetrov/Java-Text-Editor"><kbd>Learn more →</kbd></a>

---

## 2) PharmacyAccountingApp
<div id="PharmacyAccountingApp"></div>
<img width="877" height="656" alt="395849680-c5dcb118-ce2c-4211-860a-553c316e98f4" src="https://github.com/user-attachments/assets/36ac9d75-fb83-4d27-bf5d-549a9816209a" />

A Swing application for **pharmacy record management** with login, tabs for Medications and Vendors, editable tables, and a splash screen on start. Great as a foundation for CRUD-style desktop apps.

**Key Features**
- **Login:** fixed credentials (`admin` / `admin`)
- **Medications:** add/edit/delete (ID, name, stock, price)
- **Vendors:** manage vendor list (ID, name, contacts)
- **Tabbed UI:** `JTabbedPane` for smooth navigation
- **Splash screen:** 3-second image on launch
- Dynamic tables via `DefaultTableModel` with sample data

**Technical Details**
- Java (JDK 8+)
- `javax.swing`, `java.awt`

<a href="https://github.com/NicolasPetrov/Accounting-for-pharmacies"><kbd>Learn more →</kbd></a>

---

## 3) Tic-Tac-Toe
<div id="TicTacToe"></div>
<img width="469" height="460" alt="395848656-b4e8d345-84ea-46c5-848e-a96d087f03d1" src="https://github.com/user-attachments/assets/5b76af9d-139d-42b1-b215-d81fc4ef402d" />

A functional **Tic-Tac-Toe** game with a graphical interface, win detection, and restart capability. Built to practice core Java and simple game logic (UI implemented with **JavaFX**).

**Key Features**
- Player turns with input handling
- Win/draw detection and status display
- **Restart** game action
- Panel/board rendering

**Technical Details**
- Java (JDK 8+), **JavaFX**

<a href="https://github.com/NicolasPetrov/Tic-Tac-Toe-game"><kbd>Learn more →</kbd></a>

---

## 4) Snake
<div id="Snake"></div>
<img width="877" height="656" alt="480068896-79cd5d71-e06d-4c89-b97a-79bb1c621252" src="https://github.com/user-attachments/assets/6b0a61bd-f8e5-4096-a824-7ffe51018ca1" />

The classic **Snake** with difficulty levels, adaptive speed, scoring, special-food bonuses, and sound/music.

**Key Features**
- Difficulty: **easy / medium / high** (initial speed varies)
- Adaptive speed based on score (`adjustSpeed()` updates timer delay)
- Scoring: +10 for regular food
- **Special food:** +50 points; ~20% spawn chance (handled in `spawnFood()` and checked in `move()`)
- Sound effects and background music  
  *(Music generated with Suno; SFX from https://zvukipro.com/eda-napitki/253-zvuki-poedaniya-edy.html)*

**Technical Details**
- Java (JDK 8+), Swing/Timer (or JavaFX timeline depending on implementation)

<a href="https://github.com/NicolasPetrov/Snake-game"><kbd>Learn more →</kbd></a>

---

## 5) ATM App
<div id="ATMApp"></div>
<img width="473" height="475" alt="395855418-ff1d44ea-750f-4bb1-bb07-cc67b33ef17d" src="https://github.com/user-attachments/assets/adf30f96-b30e-42f7-b0dc-ef2f69fdd9c8" />

An **ATM interface** with login, balance check, transaction view, deposit, and withdrawal. GUI built with Swing; good practice for event-driven UI and basic business logic.

**Key Features**
- Login flow
- Balance overview
- View transactions
- Deposit / Withdraw with input validation

**Technical Details**
- Java (JDK 8+), **Swing**

<a href="https://github.com/NicolasPetrov/ATM-simulator"><kbd>Learn more →</kbd></a>

---

## 6) Currency Converter
<div id="CurrencyConverter"></div>
<img width="623" height="281" alt="395875127-946be650-cf73-4e2b-bf86-77006b1cc491" src="https://github.com/user-attachments/assets/42ceae8e-15dd-49bc-ab16-afa9f272696b" />

A simple **currency converter** using **CurrencyLayer** for live exchange rates. Supports USD, EUR, CHF, GBP, JPY, CNY, RUB.

**Key Features**
- Convert between supported currencies
- Fetch current rates from CurrencyLayer (API key required)

**Technical Details**
- Java (JDK 8+), HTTP client (e.g., `HttpURLConnection` or similar)

<a href="https://github.com/NicolasPetrov/Currency-Converter"><kbd>Learn more →</kbd></a>

---

## 7) Conway’s Game of Life
<div id="ConwaysGameofLife"></div>
<img width="518" height="492" alt="395851452-7861b84e-555c-4a6d-a880-445937a70ba6" src="https://github.com/user-attachments/assets/4cf73b9b-9392-4e51-8ee9-2e9f6d876bde" />

An implementation of **Conway’s Game of Life** with a graphical grid and button controls. Users place or randomize the initial state; the simulation evolves by rules with cycle/stability detection.

**Key Features**
- Start/Stop, Step, Clear/Randomize
- Alive = black, Dead = white; grid lines in grey
- Stops when:
  - no live cells remain; or
  - next state repeats a previous configuration (periodic); or
  - no cells change (stable configuration)

**Technical Details**
- Java (JDK 8+), Swing (or JavaFX) for GUI

<a href="https://github.com/NicolasPetrov/Conway_s_Game_o_Life"><kbd>Learn more →</kbd></a>
