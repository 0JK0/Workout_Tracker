# 🚀 Release v1.0.0 – Initial Terminal-Based Workout Tracker

Status: Working

Stage: Alpha

Known Limitations: No delete functionality in the History Table, Expect bugs with unexpected input.

## 🧰 Features

    Terminal-based Workout Tracker App built with Python and SQLite

    Browse and manage user pre-defined workout routines

    Saves routine history with date and time spent

    TUI-based (Terminal User Interface)

    Modular design

##  How to Use
### ✅ Quick Install

1. Go to the [Releases tab](https://github.com/0JK0/Workout_Tracker/releases/tag/Release)

2. Download the executable for your OS (only Linux rn)

3. Open a terminal in the download folder and run the file

### 🛠 Manual Install 
**(Only Option If Windows User!!)**

    Download all 4 necessary .py files

    Run main.py in your terminal or VSCode

    Admin permission might be needed (to allow local database creation)

Note: If the script can’t create a new local .db file, it will crash. Use VSCode or run with elevated permissions to avoid issues.

## 📖 Usage Flow

    Start the app → Choose an option:

        1. Show Routines

        2. Show Workout History

    If Show Routines:

        Select a routine

        Choose: View, Use, or Update

            View: displays full routine

            Use: interactive workout with rest timers, saves history

            Update: edit sets/reps/workouts, then return to View

    If Show Workout History:

        Displays your workout logs

        Choose to Quit or Return to Menu


This release serves as a functional prototype of a terminal-native fitness tracking tool. Perfect for personal use, hacking on features, or extending into a GUI-based app later.
