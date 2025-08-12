# 🎮 Custom Game Engine

> **A simple C++ game engine built with Raylib for rapid development**

---

## 🚀 **Quick Start**

### **Build**
```bash
mkdir build
cd build
cmake ..
cmake --build .
```

### **Run**
Navigate to: `build/x64-debug/` and run the executable

---

## 📁 **Project Structure**

```
2D-GameEngine/
├── Assets/              # Game assets 
├── Editor/              # Editor source
├── Engine/              # Core engine
├── Game/                # Game project
├── GameLogic/           
│   ├── MyMap.cpp        # Your game map
│   └── MyMap.h          
├── Bubble.h            
├── CMakeLists.txt      
└── README.md           
```

**Build Output:** `build/x64-debug/` (contains executable)

---

## 🎯 **How to Use**

1. **Run the Game**
   ```bash
   cd build/x64-debug
   ./main.exe
   ```

2. **Edit Your Game**
   - Modify `MyMap.cpp` to change your game
   - Create new maps by copying MyMap files
   - Customize game logic as needed

3. **Hot Reload** ⚡
   - Make changes to your code
   - Press **`Ctrl + B`** to rebuild
   - See changes instantly!

4. **Create Multiple Maps**
   - Duplicate `MyMap.cpp` and `MyMap.h`
   - Rename them (e.g., `Level1.cpp`, `Boss.cpp`)
   - Merge maps to build complete games

---

## 🔄 **Development Cycle**

```
Edit Code → Press Ctrl+B → Auto Build → See Changes → Repeat
```

**Perfect for rapid prototyping and testing!**

---

## ⚠️ **Status**

This engine is **currently in development** - perfect for:
- ✅ Testing game ideas
- ✅ Learning game development  
- ✅ Rapid prototyping
- ❌ Production games (not yet)

---

## ⭐ **Like This Project?**

**Star the repository** if you find it useful!

---

## 🛠️ **Tech Stack**
- **C++17/20** - Core language
- **Raylib** - Graphics & Input
- **CMake** - Build system

---

<div align="center">

**Happy Game Development! 🎮**

</div>
