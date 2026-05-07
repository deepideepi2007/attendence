# 🎓 Smart Study Planner Generator

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com)

A premium, AI-powered study schedule generator designed to optimize exam preparation. This application uses a weighted scoring algorithm to prioritize subjects based on difficulty, exam proximity, and personal weaknesses, all wrapped in a stunning, high-performance "Glassmorphism" interface.

![Project Preview](https://via.placeholder.com/1200x600/05050f/00f3ff?text=Smart+Study+Planner+Generator+Phase+5)

## ✨ Phase 5: Advanced Premium Experience
The latest update introduces high-end interactive elements:
- **3D Interactive Cards**: Hover over any result card to see it tilt in 3D space with a magnetic neon glow following your cursor.
- **Intensity Heatmap**: The weekly plan dynamically color-codes days based on study load (Low, Medium, High, Max).
- **Scroll Reveal**: Sections glide into view smoothly as you scroll, creating a cinematic experience.
- **Micro-interactions**: Shimmering headers on success, pulsing break reminders, and an enhanced "Cyber" loading spinner.

## 🚀 Key Features
- **Smart Priority Scoring**: Subjects are ranked using a data-science-driven algorithm (Urgency + Difficulty + Weakness).
- **Live Countdown Timers**: Real-time ticking countdowns for every upcoming exam.
- **Dynamic Timetables**: Generates both a detailed daily slot-by-slot schedule and a 7-day weekly overview.
- **Live Break System**: A persistent banner that tracks your next scheduled break and provides productivity tips.
- **Data Visualization**: Interactive Doughnut and Stacked Bar charts powered by Chart.js.
- **Export Options**: Download your optimized plan as a CSV or print it directly from the browser.

## 🛠️ Technology Stack
- **Backend**: Python (Flask)
- **Frontend**: HTML5, Vanilla CSS3 (Modern Grid/Flexbox), JavaScript (ES6+)
- **Visuals**: Chart.js for data insights
- **Deployment**: Optimized for Render (Blueprint compatible)

## 📦 Installation & Local Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/M-Awad-27/Smart-Study-Planner-Generator.git
   cd Smart-Study-Planner-Generator
   ```

2. **Set up a virtual environment (Optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   python app.py
   ```
   Access the app at `http://127.0.0.1:5000`.

## 🌐 Deployment (Render)
This project is pre-configured for Render via `render.yaml`.
1. Push your code to GitHub.
2. Connect your repo to [Render](https://render.com).
3. Select **Blueprint** deployment.
4. Render will automatically deploy the app on the **Free Tier**.

## 🤝 Contributing
Contributions are welcome! If you have ideas for Phase 6 (e.g., Google Calendar integration, user accounts), feel free to open a Pull Request.

---
**Made with ❤️ by [Muhammad Awad](https://github.com/M-Awad-27)**