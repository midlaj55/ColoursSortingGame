# 🎨 Colour Sort – SwiftUI Game

Colour Sort is a visually engaging puzzle game built using **SwiftUI**. The objective is simple: sort the colored layers into bottles until each bottle contains only one color. The project demonstrates clean architecture, smooth animations, and modern iOS development practices.

---

## 📱 Preview

- Animated splash screen  
- 3-column responsive grid layout  
- Smooth bottle pouring animations  
- Automatic bottle completion detection  

---

## 🚀 Features

- 🧪 Interactive bottle selection and pouring logic  
- 🎯 Smart move validation (only valid moves allowed)  
- ✨ Smooth horizontal & vertical pour animations  
- 🏆 Auto-detection of completed bottles  
- 🔄 Restart game functionality  
- 🎨 Modern gradient UI design  

---

## 🛠 Tech Stack

- **Swift**
- **SwiftUI**
- **MVVM Architecture**
- **Combine**
- Custom Shapes & Animations

---

## 🧠 Game Rules

- Each color appears exactly **4 times**.
- Each bottle has a maximum capacity of **4 layers**.
- You can only pour:
  - Into an empty bottle  
  - Or onto the same color  
- Multiple same-color layers pour together automatically.
- A bottle is marked complete when all layers match.

---

## 🏗 Architecture

The project follows the **MVVM pattern**:

- `GameViewModel` handles game logic and state management.
- `BottleView` renders each bottle UI.
- `BottleModel` represents bottle data.
- SwiftUI views reactively update using `@Published` properties.

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/colourSortGame.git
