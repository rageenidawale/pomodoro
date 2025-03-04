# 🍅 Pomodoro Timer

## Overview
This is a **Pomodoro Timer** built using Python and Tkinter. The Pomodoro technique helps improve productivity by alternating work and break sessions. This app guides users through **25-minute work intervals**, followed by **short and long breaks**.

## Features
- ✅ 25-minute work sessions
- ✅ 5-minute short breaks after each session
- ✅ 20-minute long breaks after every 4 work sessions
- ✅ Visual timer countdown
- ✅ Checkmarks to track completed sessions
- ✅ Start and Reset buttons

## Requirements
- Python 3.x
- Tkinter (built-in with Python)

## Installation & Usage
1. Clone or download this repository.
2. Ensure you have `tomato.png` in the same directory as the script.
3. Run the script:
   ```bash
   python pomodoro_timer.py
   ```
4. Click **Start** to begin the timer.
5. Click **Reset** to stop and reset the timer.

## File Structure
```
|-- pomodoro_timer.py  # Main script
|-- tomato.png         # Image used in the UI
```

## How It Works
1. **Start Timer**:
   - The app begins with a 25-minute work session.
   - A short 5-minute break follows.
   - After 4 work sessions, a long 20-minute break occurs.
   - The cycle repeats.
2. **Reset Timer**:
   - Stops the countdown and resets the timer.

## Example Usage
1. Open the app and press **Start**.
2. Work until the timer hits **00:00**.
3. Take a short/long break when prompted.
4. The app keeps track of completed sessions with checkmarks (`✔`).

## Future Enhancements
- Add sound alerts for session changes.
- Allow custom session durations.
- Save session history.

Stay focused and productive with the **Pomodoro Timer!** 🍅
