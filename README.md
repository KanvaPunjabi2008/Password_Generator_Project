# 🔐 PyPassword Generator

A simple, interactive command-line tool built with Python that generates strong, randomized passwords based on user preferences.

---

## ✨ Features

* **Interactive CLI**: Prompts the user for specific counts of letters, symbols, and numbers.
* **True Randomization**: Uses Python's `random` module to pull unpredictable characters.
* **Enhanced Security**: Automatically shuffles the final character order so patterns are completely broken down.

---

## 🛠️ Tech Stack

* **Language**: Python 3.x
* **Core Modules**: `random`

---

## 💻 Getting Started

Follow these simple steps to run the password generator on your local machine.

### Prerequisites
Make sure you have Python 3 installed. You can check your version by running:
```bash
python --version
```

### Installation & Execution
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```

2. **Navigate into the project directory:**
   ```bash
   cd YOUR-REPOSITORY-NAME
   ```

3. **Run the script:**
   ```bash
   python main.py
   ```

---

## ⚙️ How It Works

When you run the script, it walks you through three simple questions:
1. **Letters**: Enter how many alphabet characters (uppercase or lowercase) you want.
2. **Symbols**: Enter how many special characters (e.g., `!`, `#`, `$`) you want.
3. **Numbers**: Enter how many numeric digits you want.

### Execution Flow:
* The script collects random choices from the predefined character lists into a temporary list.
* It prints the initial ordered list.
* It runs `random.shuffle()` to scramble the positions of all characters.
* It prints the scrambled list and outputs your final secure password string.

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.
