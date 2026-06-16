# ThermoLux – Temperature Converter 🌡️

A modern and elegant **Temperature Converter Web Application** built using **HTML, CSS, and JavaScript**. ThermoLux allows users to convert temperatures between **Celsius (°C), Fahrenheit (°F), and Kelvin (K)** instantly while providing a beautiful user interface, conversion history, statistics tracking, and dark mode support.

---

## 📌 Project Overview

ThermoLux is designed to provide accurate temperature conversions with an enhanced user experience. The application features a Pinterest-inspired aesthetic UI, glassmorphism design, responsive layout, and interactive animations.

The project demonstrates core frontend development concepts including:

- HTML5 semantic structure
- Advanced CSS styling and animations
- JavaScript DOM manipulation
- Local Storage integration
- Responsive Web Design
- User Experience (UX) enhancements

---

## ✨ Features

### 🌡️ Temperature Conversion
- Celsius ↔ Fahrenheit
- Celsius ↔ Kelvin
- Fahrenheit ↔ Kelvin

### 🎨 Modern User Interface
- Glassmorphism-inspired design
- Elegant typography using Google Fonts
- Smooth hover effects and animations
- Floating decorative elements

### 🌙 Dark Mode
- Light and Dark theme switching
- Theme preference saved using Local Storage

### 📊 Statistics Dashboard
Tracks:
- Total conversions
- Today's conversions
- Most frequently used unit
- Last converted temperature

### 📜 Conversion History
- Stores previous conversions
- Delete individual history items
- Clear all history option
- Persistent storage using Local Storage

### ⭐ Frequently Used Conversions
Displays the most commonly used conversion pairs.

### 📋 Copy Result
Allows users to copy conversion results directly to the clipboard.

### ✅ Input Validation
- Prevents empty inputs
- Detects invalid numbers
- Prevents negative Kelvin values

### 📱 Fully Responsive
Optimized for desktop, tablet, and mobile devices.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| HTML5 | Structure of the application |
| CSS3 | Styling and animations |
| JavaScript (ES6) | Functionality and logic |
| Local Storage | Data persistence |
| Google Fonts | Typography |

---

## 📂 Project Structure

```text
ThermoLux/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🚀 How It Works

1. User enters a temperature value.
2. Select source and target units.
3. Click **Convert Temperature**.
4. The application calculates and displays the result.
5. Conversion history and statistics are automatically updated.

---

## 🔄 Conversion Formulas

- °F = (°C × 9/5) + 32
- K = °C + 273.15
- °C = (°F − 32) × 5/9
- K = (°F − 32) × 5/9 + 273.15
- °C = K − 273.15
- °F = (K − 273.15) × 9/5 + 32

---

## 💾 Local Storage Keys

- `thermolux_history`
- `thermolux_stats`
- `thermolux_freq`
- `thermolux_theme`

---

## 🎯 Key JavaScript Functions

- `doConvert()` – Performs conversion and validation
- `applyTheme()` – Handles dark/light mode
- `renderHistory()` – Displays conversion history
- `updateStats()` – Updates dashboard statistics
- `showToast()` – Displays notifications

---

## 🔮 Future Enhancements

- Rankine temperature scale support
- Export history as PDF/CSV
- Data visualization charts
- Multi-language support
- Progressive Web App (PWA)

---

## 🎓 Learning Outcomes

- Frontend Development
- DOM Manipulation
- Event Handling
- Local Storage API
- Responsive Design
- CSS Animations
- Modern UI/UX Design

---

## 👨‍💻 Author

**ThermoLux – Temperature Converter**

Developed as part of a Frontend Web Development Internship Project.

---

## 📜 License

This project is for educational and internship demonstration purposes.
