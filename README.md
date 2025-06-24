# 🔩 Rivet Integrity Tester

A **web-based 3D simulation** tool to assess rivet integrity under variable tensile and shear forces. Designed for engineers and students, it provides real-time visual feedback, score computation, and material breakdowns. Built with **Three.js**, it includes dark mode, result exports, and persistent local test history.

---

## 🎯 Features

- 🏭 **Industry-Specific Rivet Types**  
  Choose between Aerospace, Shipbuilding, or Structural Engineering to get relevant rivet materials and specs.

- 💥 **Live Force Simulation**  
  Drag sliders for **shear** and **tensile** force (in kN) to see how the rivet reacts in real time.

- 💡 **3D Visualization**  
  Animated rivet geometry reacts to force and may **fail** dynamically, splitting in a realistic 3D rupture using **Three.js**.

- 📊 **Test Output Panel**  
  Displays:
  - Material
  - Diameter
  - Shear Strength
  - Calculated Integrity Score

- 💾 **Save + Export Results**  
  - Save simulation data to localStorage
  - Export as plain-text `.txt` report

- 🌙 **Dark Mode Toggle**  
  Persistent theme switcher built with Tailwind CSS and localStorage.

- 📚 **Test History Modal**  
  View past tests with timestamps in a modal window.

