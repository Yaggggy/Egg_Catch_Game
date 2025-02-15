# Egg Catcher Game

A simple and fun egg-catching game built using Python and Tkinter.

## 🎮 Game Overview
- Move the basket left and right using arrow keys to catch falling eggs.
- Each caught egg increases your score by **10 points**.
- If an egg hits the ground, you lose a life.
- The game gets harder as eggs fall faster over time.
- The game ends when you run out of lives.

## 🛠️ Installation & Setup

### Prerequisites
Ensure you have **Python 3.x** installed on your system.

### Run the Game
1. Clone this repository or download the `egggame.py` file.
2. Open a terminal or command prompt in the script directory.
3. Run the following command:
   ```sh
   python egggame.py
   ```

## 🎮 Controls
- **Left Arrow (`←`)** → Move catcher left
- **Right Arrow (`→`)** → Move catcher right

## 📜 Features
✅ Randomly generated falling eggs 🎭  
✅ Different colored eggs 🌈  
✅ Increasing difficulty over time ⏳  
✅ Score and life tracking 📊  
✅ Game over message when lives run out ❌  

## 🔧 Customization
Want to tweak the game? Modify these variables in `egggame.py`:
```python
egg_speed = 500  # Adjust egg falling speed
egg_interval = 4000  # Adjust egg spawn rate
difficulty = 0.95  # Change difficulty scaling
catcher_color = "blue"  # Change catcher color
```

## 📌 Known Issues & Fixes
### `AttributeError: module 'random' has no attribute 'randint'`
This happens if you have a file named `random.py` in the same directory. Fix it by renaming or deleting `random.py`.

## 📜 License
This project is open-source and free to use.

## 🤝 Contributing
Feel free to fork the project and add new features! 🚀

## 📩 Contact
For questions or improvements, open an issue or reach out! 🎮

