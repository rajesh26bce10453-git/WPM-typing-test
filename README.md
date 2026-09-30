# Speed Typing Test ⌨️

A simple, terminal-based typing speed test built using Python. The program displays a random piece of text and lets you type it while tracking your typing speed in words per minute (WPM).

The project uses Python's built-in `curses` module to create an interactive interface directly in the terminal.

## Features

* **Real-time WPM:** See your typing speed as you type.
* **Color-coded feedback:** Correct characters appear in green, while incorrect ones are highlighted in red.
* **Random text:** Each round selects a random passage from `text.txt`.
* **Backspace support:** Made a typo? You can correct it while typing.
* **Continuous testing:** Complete one round and start another without restarting the program.
* **Keyboard controls:** Press `ESC` to exit a typing test.

## Tech Stack

* Python
* Curses
* Random
* Time

All the libraries used in this project are included with Python, so no additional packages are required.

## Project Structure

```text
Speed-Typing-Test/
│
├── main.py       # Main application
├── text.txt      # Text passages for typing tests
└── README.md     # Project documentation
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/rajesh26bce10453-git/WPM-typing-test.git
```

### 2. Navigate to the project directory

```bash
cd WPM_Typing_Test
```

### 3. Run the program

```bash
python main.py
```

Make sure Python is installed on your system before running the program.

**Note:** The `curses` module is included with Python on Linux and macOS. On Windows, you may need to install `windows-curses`:

```bash
pip install windows-curses
```

## How to Use

1. Run the program in your terminal.
2. Press any key to start the typing test.
3. Type the displayed text as accurately and quickly as possible.
4. Your WPM will update as you type.
5. Correct mistakes using Backspace.
6. Once you finish the passage, press any key to start another round.
7. Press `ESC` to exit.

## How Is WPM Calculated?

The program calculates typing speed using the number of characters typed and the time elapsed.

It uses the standard approximation that **5 characters equal one word**.

The formula is:

```text
WPM = (Characters Typed / 5) / Time in Minutes
```

The result is rounded to the nearest whole number and updated continuously during the test.

## Customizing the Test

You can add your own passages to `text.txt`.

Simply add each new passage on a separate line. The program will randomly select one whenever a new test begins.

## Author

Name: Rajesh Paine

Reg No: 26BCE10453
