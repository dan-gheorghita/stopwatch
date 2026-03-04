# stopwatch.py

**Stopwatch Program Analysis**

The provided Python code implements a simple stopwatch program using the `time` module. Here's a breakdown of its functionality:

### Program Flow

1. **Initialization**: The program displays instructions to the user, prompting them to press Enter to begin the stopwatch.
2. **Start**: After pressing Enter, the stopwatch starts, and the first lap's start time is recorded using `time.time()`.
3. **Lap Tracking**: The program enters an infinite loop, waiting for the user to press Enter to record each lap's time.
4. **Time Calculation**: On each lap, the program calculates the lap time by subtracting the last lap's start time from the current time. It also calculates the total time elapsed since the stopwatch started.
5. **Output**: The program prints the lap number, total time, and lap time, rounded to two decimal places.
6. **Quit**: When the user presses Ctrl-C, the program catches the `KeyboardInterrupt`