<div align="center">

```
          /\
         /  \
        /^^^^\
       /      \
      /  /\    \
     /  /  \    \
    /__/____\____\        AETHER ENGINE
   /\  ____  ____  /\     -----------------
  /  \/   /\/   /\/  \    A low-poly 3D engine built from scratch
 /__/____/__/__/____/__\   in Java 25 + LWJGL 3 + JOML
```

</div>

---

## 🌌 Aether Engine
**A custom low-poly 3D engine built from scratch in Java** using [LWJGL 3](https://www.lwjgl.org/), [GLFW](https://www.glfw.org/), [OpenGL](https://www.khronos.org/opengl/), and [JOML](https://joml-ci.github.io/JOML/).  
Running on **Java 25 LTS**, powered by pure curiosity and chaos.

---

### 🚀 Features
- ✅ Custom engine core written entirely in **Java 25**
- 🎮 **LWJGL 3** bindings for graphics, input, and audio  
- 🧮 **JOML** for vector and matrix math  
- 🪟 Native **OpenGL GLFW** window management  
- 🏗️ Low-poly-style rendering & procedural world generation *(in progress)*  

---

### 🧰 Tech Stack
| Component    | Library          | Version |
| ------------ | ---------------- | ------- |
| Language     | Java             | 25 LTS  |
| Build System | Maven            | 3.9.11  |
| Graphics     | LWJGL 3 + OpenGL | 3.3.6   |
| Window/Input | GLFW             | 3.3.6   |
| Math Library | JOML             | 1.10.8  |

---

### ⚙️ Setup & Run

#### 1️⃣ Requirements
- Java 25 LTS  
- Maven 3.9+  
- *(Optional)* VS Code with *Extension Pack for Java*

#### 2️⃣ Clone
```powershell
git clone https://github.com/etherOnGitHub/aether-engine.git
cd aether-engine
```

#### 3️⃣ Build & Run
```powershell
mvn clean compile
mvn exec:java
```

A window titled **“Aether Engine”** should appear — your first frame from the void 👁️  

---

### 🪶 Roadmap
- [ ] Basic render loop  
- [ ] Vertex buffers + shaders  
- [ ] Camera and transforms  
- [ ] Entity / scene system  
- [ ] Terrain generation  
- [ ] Physics integration  
- [ ] Editor tooling  

---

### 🧠 About
> *“In the beginning, there was only the void…  
> then someone wrote a main method.”*

Aether Engine is an experimental sandbox for learning the dark arts of engine development. Expect broken math, glowing triangles, and the occasional existential bug.

---

### 💾 License
MIT License — free to fork, learn, and expand.
