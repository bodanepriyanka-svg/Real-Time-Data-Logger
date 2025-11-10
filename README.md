# Real-Time-Data-Logger
A small C program (main.c) that:
1.Simulates temperature and humidity (random-walk).
  i.Appends timestamped readings to a CSV (data.csv by default).
  ii.Prints readings to the terminal in real time.
  iii.Handles Ctrl+C (SIGINT) for graceful shutdown.
2.Makefile to build the program.
3.README.md with usage and instructions to push to GitHub.
4.gitignore and LICENSE.
5.A zip archive containing the project.

CODE:-
git init
git add .
git commit -m "Initial commit - Real-Time Data Logger"
git remote add origin https://github.com/<your-username>/real-time-data-logger.git
git branch -M main
git push -u origin main

If you want, I can:
Add timestamped filenames (e.g., readings_2025-11-10_0830.csv) automatically.
Add command-line options parsing (e.g., using getopt) for more control.
Convert the logger to write JSON or add rotating logs.
Provide a ready gh CLI script or GitHub Actions workflow for automatic releases.

CONCLUSION:-
The Real-Time Data Logger project successfully demonstrates how real-time data can be simulated, collected, displayed, and stored using a simple C program. It efficiently logs parameters such as temperature and humidity with accurate timestamps, providing both on-screen monitoring and permanent data storage in a CSV file.
This project highlights the fundamental principles of data acquisition systems, file handling, and real-time processing. It also illustrates how embedded and software-based loggers can be designed for monitoring applications without requiring external hardware sensors.
In conclusion, this project provides a practical understanding of:
  Real-time data simulation and logging concepts.
  Handling time and file operations in C.
  Implementing a simple, reliable, and extendable data-logging mechanism.
  It forms a solid foundation for future enhancements, such as integrating actual sensor data, graphical visualization, or IoT connectivity for remote monitoring and analysis.
