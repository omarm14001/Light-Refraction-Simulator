# Light-Refraction-Simulator

# 🌐 Light Refraction & Total Internal Reflection Simulator
An interactive Python-based desktop simulator that visualizes the physics principles of *Light Refraction* (Snell's Law) and *Total Internal Reflection (TIR)* in real-time. 
Built using Tkinter for seamless user input and Turtle Graphics for smooth, accurate rendering.
---
## 🚀 Features
* *Custom Mediums:* Input any refractive indices ($n_1$ and $n_2$) via a clean GUI popup before the simulation starts.
* *Real-time Interaction:* Dynamically change the incident angle of the light beam using keyboard controls.
* *Physics-Accurate Simulation:* * Accurately calculates the refraction angle ($\theta_2$) using Snell's Law: 
    $$n_1 \sin(\theta_1) = n_2 \sin(\theta_2)$$
  * Automatically detects and simulates *Total Internal Reflection* when the incident angle exceeds the critical angle:
    $$\theta_c = \arcsin\left(\frac{n_2}{n_1}\right)$$
* *High Performance:* Implements frame tracing (wn.tracer(0)) for smooth, lag-free rendering at ~60 FPS.
---
## 🎮 How to Control
Once the simulation window opens, you can control the light source using your keyboard:

| Key | Action |
| :--- | :--- |
| *W* | Increase the incident angle (Move light beam Up) |
| *S* | Decrease the incident angle (Move light beam Down) |

---
## 🛠️ Tech Stack & Requirements
* *Language:* Python 3.x
* *Built-in Libraries:* * tkinter (GUI Input Window)
  * turtle (Graphics & Animation Engine)
  * math (Trigonometric & Physics Calculations)
No external dependencies are required!
---
## 💻 Installation & Running
1. *Clone the repository:*
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME
