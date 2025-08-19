# Stopwatch Project ⏱️

A simple GUI-based stopwatch application using **Python** and **PyQt5**. This project is suitable for Python programming practice and desktop interface development.

## 🖼️ Preview

<div align="center">
  <img src="image.png" alt="stopwatch display" width="600"/>
</div>

The stopwatch displays time in **hour:minute:second:millisecond** format and has three buttons:
- **Start**: Starts the stopwatch
- **Stop**: Stops the stopwatch
- **Reset**: Resets the time to zero

## 🛠️ Technology Used

- Python 3
- PyQt5

## ⚙️ How to Run

1. **Clone this repository:**

   ```bash
   git clone https://github.com/Rukadevata/Stopwatch-Project.git
   cd Stopwatch-Project

2. **Make sure PyQt5 is installed (if not already):**
   ```bash
   pip install PyQt5

3. **Run the application:**
   ```bash
   python main.py

## 📌 Notes
- This application uses **QTimer** to calculate time and **QTime** as the current time storage.
- The views are created with **QVBoxLayout** and **QHBoxLayout**, and styled using **setStyleSheet**.