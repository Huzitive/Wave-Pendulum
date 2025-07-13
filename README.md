
# 🌊 Wave Pendulum Simulation – NEDUET Physics

This web-based interactive simulation demonstrates the physics of pendulum waves. Created using pure HTML, CSS, and JavaScript, it visualizes the motion of multiple pendulums of varying lengths and simulates wave-like interference patterns over time.

> ✅ **Created by:** *Huzaifa Ahmed Khan*
> 👩‍🏫 **Under the Supervision of:** *Ms. Marium Ghulam Nabi*
> 🏫 *Department of Physics, NED University of Engineering & Technology*

---

## 🧠 Physics Behind the Simulation

The motion of each pendulum follows the classical harmonic equation:

$$
\theta(t) = \theta_0 \cos\left(\sqrt{\frac{g}{L}} \, t\right)
$$

Where:

* **$\theta(t)$** – Angular displacement at time $t$
* **$\theta_0$** – Initial angle
* **$g$** – Gravitational acceleration
* **$L$** – Length of pendulum

By using pendulums of slightly varying lengths, their oscillations fall in and out of phase, creating beautiful wave-like patterns.

---

## 🛠 Features

* 🎛️ Adjustable parameters:

  * Number of pendulums
  * Shortest & longest pendulum length
  * Gravity
  * Initial angle
* 🎨 Toggle **motion trails** for visual effects
* 📈 Real-time graph of $\theta(t)$ for the first pendulum using Chart.js
* 📤 Export graph data as:

  * PNG image
  * CSV data
* 📱 Responsive UI (scales well on various screen sizes)

---

## 📂 File Structure

```
wave-pendulum-simulation/
│
├── index.html       # Main simulation page
├── style (inline)   # Embedded CSS styling
└── script (inline)  # JS logic for pendulum physics, animation & charting
```

---

## 🚀 Getting Started

### ✅ Prerequisites

No installations or builds needed. This simulation is pure HTML/CSS/JS.

### ▶️ Run Locally

1. **Clone this repository**

   ```bash
   git clone https://github.com/your-username/wave-pendulum-simulation.git
   ```

2. **Open `index.html` in any modern browser**

---

## 🧪 Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* [MathJax](https://www.mathjax.org/) – for LaTeX math rendering
* [Chart.js](https://www.chartjs.org/) – for plotting angular motion

---

## 📤 Exports

* `Export PNG`: Download the graph as a `.png` image
* `Export CSV`: Download time-angle data for further analysis

---

## 📜 License

This project is for academic and educational purposes. Contact the author if you'd like to reuse or build upon this work.

---



