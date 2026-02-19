# 🟢 Leap-Frog-Puzzel

A **4x4 JavaFX puzzle game** where you jump balls over each other to remove them.  

---

## 🎯 Goal
- Reduce the board to a **single ball** to win.  
- If no valid moves remain, you lose.  

---

## 🕹️ How to Play
- Each cell may have a ball and up to four **directional buttons**:  
  - **↑ Up** | **↓ Down** | **← Left** | **→ Right**  
- Click a button to **jump a ball over an adjacent ball** into an empty space.  
- The jumped-over ball is **removed** automatically.  
- Valid moves are indicated by visible buttons; impossible moves are hidden.  

---

## 📊 UI
- **Top label** shows:
  - Balls left
  - Possible moves
  - Win/Lose messages
- The board updates after every move, showing only valid jumps.  

---

## ⚡ Features
- Interactive JavaFX grid
- Dynamic button visibility
- Real-time move and ball count updates
