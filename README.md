# 🎯 Angry Birds Physics Clone (Unity 2D)

This project is a 2D physics-based projectile game inspired by *Angry Birds*, built using Unity.  
Along with development, this project was also approached from a **Quality Assurance perspective**, focusing on iterative testing, bug reporting, and gameplay refinement.

---

## 🧠 Project Purpose

- Learn and implement physics-based gameplay using Unity (Rigidbody2D + Colliders)
- Practice **manual QA testing** in a real game project
- Track bugs and apply regression testing after fixes
- Improve overall user experience through analysis and iteration

---

## 🕹️ Gameplay Features

✔ Drag-and-release slingshot mechanic  
✔ Realistic projectile physics  
✔ Collisions with destructible objects  
✔ Restart level functionality  
✔ Smooth trajectory experience after multiple refinements  

---

## 🔧 Tech Stack

| Component | Tool |
|----------|------|
| Game Engine | Unity 2D |
| Scripting Language | C# |
| Testing Style | Manual QA + Regression Testing |
| Version Control | Git / GitHub |
| Build Output | Windows EXE / WebGL (optional) |

---

## 🧪 QA Testing Summary

This project includes structured testing to validate behavior and gameplay logic.

### 🧩 Testing Types Performed

| Testing Method | Applied |
|---------------|---------|
| Functional Testing | ✔ |
| Exploratory Testing | ✔ |
| Regression Testing | ✔ |
| Input Boundary Testing | ✔ |
| Physics & Collision Validation | ✔ |

---

## 📝 Example Test Cases

| Test Case | Expected Behavior | Status |
|----------|-------------------|--------|
| Drag bird and release | Bird launches smoothly | ✔ Pass |
| Zero-drag release | Bird drops near slingshot, no bugs | ✔ Pass |
| Full drag force | Bird follows stable projectile arc | ✔ Pass |
| Collision with block | Block reacts / breaks based on force | ✔ Pass |
| Restart level | All objects reset to original state | ✔ Pass |

---

## 🐞 Bugs Found and Fixed

| Issue | Root Cause | Fix Applied |
|-------|------------|-------------|
| Bird floating mid-air | Rigidbody gravity was set to 0 | Enabled gravity and tuned physics |
| Collision not registering | Wrong layer mask / missing collider | Updated collision matrix |
| Trajectory too strong | Incorrect velocity scaling | Normalized launch force |

---

## ▶️ How to Play

| Action | Control |
|--------|---------|
| Drag | Pull slingshot |
| Release | Launch bird |
| Automatic Restart level |

---

## 📂 Project Pictures



