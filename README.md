# 🎯 Hunter Hustle

> A modern Python remake of the classic light gun arcade shooter — built with Pygame.

## 🕹️ Game Overview

**Hunter Hustle** is a retro-style arcade shooting game inspired by Nintendo’s *Duck Hunt*, recreated using Python and Pygame. It features vibrant visuals, dynamic sound effects, and three challenging game modes. Players aim and shoot at moving targets using the mouse, progressing through three levels of increasing difficulty.

---

## 📽️ Gameplay Preview

<img width="1124" height="1014" alt="Screenshot 2025-07-13 004226" src="https://github.com/user-attachments/assets/bee474ad-ba77-4ac9-a9d1-533b6cea6b09" />
<br><br>
<img width="1123" height="1011" alt="Screenshot 2025-07-13 004530" src="https://github.com/user-attachments/assets/d01fcf5e-ba23-4b64-9456-01aaf449e85b" />
<br><br>
<img width="1121" height="1012" alt="Screenshot 2025-07-13 003913" src="https://github.com/user-attachments/assets/3791f5d8-72d4-48ad-a9e3-22b4499642df" />
<br><br>
<img width="1121" height="1017" alt="Screenshot 2025-07-13 003957" src="https://github.com/user-attachments/assets/af4eb47c-eaa1-4a7d-a6ab-b14725812321" />
<br><br>
<img width="1130" height="1020" alt="Screenshot 2025-07-13 004144" src="https://github.com/user-attachments/assets/955d3f04-4024-43a0-bedf-3e7162897bd6" />

---

## 🎯 Objective

To modernize a classic 1980s shooting gallery game by implementing:
- Dynamic visuals and sound effects
- Score tracking and persistence
- Multiple game modes and levels
- Cross-platform compatibility and ease of play

---

## ❓ Key Questions

- How can a legacy arcade-style shooter be modernized using Python?
- What are the effective methods for implementing aiming, shooting, and level mechanics in Pygame?
- How can player progress (like high scores) be stored locally?

---

## 🔧 Features

✅ Mouse-based aiming and shooting  
✅ Three gameplay modes: Freeplay, Ammo-limited, Timed  
✅ Three levels with birds, plates, and spaceships  
✅ Real-time scoring and high score saving  
✅ Animated gun rotation and visual effects  
✅ Pause and game over screens  
✅ Background music and sound effects

---

## 🛠️ Tech Stack

- **Programming Language**: Python 3.x  
- **Game Library**: Pygame  
- **IDE**: Visual Studio Code  
- **Assets**: images, MP3/WAV sound effects, custom font

---

## 🧪 How It Works

1. Launch the game to reach the main menu.
2. Choose a mode:  
   - Freeplay (time is score)  
   - Ammo-limited (accuracy-based)  
   - Timed (points within 30 seconds)
3. Aim with your mouse, click to shoot.
4. Targets (birds, plates, spaceships) fly across the screen at different speeds and layers.
5. Score points by hitting targets; progress through three levels.
6. Game ends when time or ammo runs out, or all targets are hit.
7. High scores are saved locally in a text file (`high_scores.txt`).

---

## 💡 Insights Gained

- Pygame offers a flexible framework for 2D games, even with minimal setup.
- Layer-based object motion introduces scalable challenge and scoring.
- Simple file I/O provides effective persistence for local high scores.

---

## 🏁 Conclusion

**Hunter Hustle** is a fully playable, engaging arcade-style game that combines nostalgia with modern implementation. It’s portable, customizable, and extensible — an excellent example of how Python can be used to recreate and improve upon classic gameplay experiences.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or later
- Pygame

### Installation

# Install dependencies
pip install pygame

# Run the game
python main.py
