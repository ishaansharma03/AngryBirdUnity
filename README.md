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

<img width="758" height="444" alt="Screenshot 2025-11-19 134653" src="https://github.com/user-attachments/assets/642027ec-6c09-47e8-aa7a-eb66dc7b68ce" />


<img width="950" height="483" alt="Screenshot 2025-11-19 134646" src="https://github.com/user-attachments/assets/ca7f1653-9577-4a1e-9429-8229f8db7f24" />


<img width="991" height="822" alt="Screenshot 2025-11-19 134639" src="https://github.com/user-attachments/assets/bda38f8b-3c13-47ac-acbb-859423977dd7" />


<img width="1230" height="605" alt="Screenshot 2025-11-19 134629" src="https://github.com/user-attachments/assets/2af20a06-d4fc-40ff-8d97-7f3cb9bd48af" />


<img width="1871" height="546" alt="Screenshot 2025-11-19 134621" src="https://github.com/user-attachments/assets/fde98c2e-67ba-4ac5-b8d4-14c2b2cbe94a" />


<img width="1600" height="821" alt="Screenshot 2025-11-19 134613" src="https://github.com/user-attachments/assets/8febc21d-c1a8-4345-a30c-8ed966482daf" />


<img width="1919" height="1017" alt="Screenshot 2025-10-28 152604" src="https://github.com/user-attachments/assets/82b5db5d-7d10-4c7c-9ad5-95238456f5f3" />


<img width="1919" height="1020" alt="Screenshot 2025-10-28 152626" src="https://github.com/user-attachments/assets/0c6623af-d991-4926-94b3-e483a6292dcc" />


<img width="1909" height="1021" alt="Screenshot 2025-10-28 152653" src="https://github.com/user-attachments/assets/2033f7ab-127a-486b-8be5-a75f76a3aed4" />

---

## 🚀 Future Enhancements

- Multiple levels and difficulty modes  
- Different bird types (bomb, speed, heavy)  
- UI polish and audio system  
- Automated play-testing script  
- Scoring system  

---

## 🏁 Status

✔ Completed core gameplay  
✔ Tested and improved  
⭕ Further improvements planned

---

## 👤 Author

**Ishaan Sharma**

- 📧 Email: ishaantaker117@gmail.com
- 🔗 LinkedIn: https://www.linkedin.com/in/ishaan-sharma-063979220/
