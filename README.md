# ⏱️ trackr - Simple Terminal Time Tracker

[![Download trackr](https://img.shields.io/badge/Download-trackr-blue?style=for-the-badge)](https://github.com/CopraVopasen/trackr/releases)

## 📋 What is trackr?

trackr is a terminal-based app designed to help you keep track of your time. It works right inside your computer’s command line window. The app lets you start timers, organize your work into projects, and generate reports on how you spent your time. It also includes a Pomodoro timer to help with focus, and options to export your data so you can use it elsewhere.

With trackr, you don’t need to switch between apps or use complicated tools. Everything happens in your terminal, making it lightweight and fast.

## 💻 What systems does trackr run on?

trackr is built using Go, a popular programming language, so it works on most computers including:

- Windows 10 or newer
- macOS 10.13 or newer
- Linux distributions (Ubuntu, Fedora, etc.)

You need a terminal application to use trackr, which your system already has by default.

## 🔧 Main Features

- Timer: Start, pause, and stop tracking time easily.
- Projects: Group tasks and time entries under project names.
- Reports: View summaries of your work by day, week, or project.
- Pomodoro: Use the Pomodoro technique with built-in timers.
- Export: Save your tracked time as CSV files for spreadsheets.
- SQLite database: Keeps your data safe and local on your computer.
- Lightweight: Run everything directly in the terminal with no extra programs.

## 🚀 Getting Started

This guide will help you download and start using trackr quickly.

### Step 1: Download trackr

Click the large blue button at the top of this page or go to:

[https://github.com/CopraVopasen/trackr/releases](https://github.com/CopraVopasen/trackr/releases)

This page has all the versions of trackr available to download.

### Step 2: Choose the right file for your computer

On the releases page, look for the latest version. Under the latest release, you will see files ending with extensions like:

- `.exe` for Windows
- `.dmg` for macOS
- `.tar.gz` or `.deb` for Linux

Download the file that matches your operating system.

### Step 3: Install trackr

- **Windows:** Double-click the `.exe` file and follow any prompts. If it's a standalone program, you might just run it directly.
- **macOS:** Open the `.dmg` file, then drag the trackr app to your Applications folder.
- **Linux:** Use your package manager if available, or extract the `.tar.gz` file and follow included instructions.

### Step 4: Open your terminal

- **Windows:** Open PowerShell or Command Prompt.
- **macOS:** Open Terminal from Applications > Utilities.
- **Linux:** Open the terminal app you normally use.

### Step 5: Run trackr

Type `trackr` and press Enter. This will launch the app in your terminal window.

## 🎯 How to use trackr

trackr uses simple commands typed into the terminal. Here are the basics to get started.

### Starting a timer

To start tracking time on a task, type:

```
trackr start [project_name]
```

Replace `[project_name]` with the name of the project you want to work on. For example:

```
trackr start marketing
```

This begins the timer for your marketing work.

### Pausing and stopping

To pause the timer:

```
trackr pause
```

To stop and save your time entry:

```
trackr stop
```

### Checking your time

To see how much time you’ve tracked today:

```
trackr report today
```

To view time spent on a project this week:

```
trackr report week marketing
```

### Using the Pomodoro timer

Start a Pomodoro session with:

```
trackr pomodoro start
```

Pause it with:

```
trackr pomodoro pause
```

Stop it with:

```
trackr pomodoro stop
```

trackr will notify you when each Pomodoro session finishes.

### Exporting your data

To export your time entries to a CSV file:

```
trackr export csv
```

This file can be opened in spreadsheet apps like Excel.

## 📥 Download & Install

Return to the download page here:

[https://github.com/CopraVopasen/trackr/releases](https://github.com/CopraVopasen/trackr/releases)

- Find the latest release at the top of the page.
- Choose the file that matches your operating system (Windows, macOS, Linux).
- Download and run that file.
- Follow the previous section’s instructions to install and launch trackr.

If you run into issues, check the 'Issues' tab on the GitHub page for help or search online for terminal basics on your OS.

## ⚙️ Configuration and Settings

trackr stores its data locally in a database file inside your home directory. You don’t need to set anything up manually. However, you can customize:

- Default project names
- Timer settings like Pomodoro durations
- Export file paths

You can change these by editing the configuration file located at:

```
~/.trackr/config.yaml
```

Open this file in any text editor. It includes comments explaining each option.

## 🛠 Troubleshooting

- If trackr does not start, make sure you installed the correct file for your OS.
- On Windows, if the program is blocked, check your antivirus or security settings.
- For permission issues on macOS/Linux, try running `chmod +x trackr` in the terminal to make it executable.
- If commands don’t work, type `trackr help` to see all available options.

## 🔄 Updates

Check the releases page regularly for new versions. Each update may include bug fixes or new features.

To update, download the latest file and replace your existing trackr program with it.

## 📚 Learning More

Use the terminal command:

```
trackr help
```

to see a full list of commands and how to use them.

Visit the GitHub repository for detailed documentation and examples:

[https://github.com/CopraVopasen/trackr](https://github.com/CopraVopasen/trackr)

## 🧰 About the Technology

trackr is built with:

- Go (Golang) – a fast and reliable programming language.
- Bubble Tea – a framework for building terminal user interfaces.
- SQLite – a simple database to store your tracked time.

This combination allows trackr to be lightweight, fast, and easy to use inside your terminal window without other software.

## 🏷 Topics

bubble-tea, cli, go, golang, pomodoro, productivity, sqlite, terminal, time-tracker, tui