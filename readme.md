# Emergency Service Directory 🚨

A responsive and interactive web application providing quick access to essential government emergency services in Bangladesh. Built with modern web development tools, this platform allows users to find hotline numbers, copy contact details, manage favorites, and maintain a call history log seamlessly.

---

## 📸 Overview

The **Emergency Service Directory** serves as a centralized hub for critical helpline numbers—including National Emergency (999), Police, Fire Service, Ambulance, Women & Child Helpline, and Anti-Corruption Hotline.

![Project Screenshot](assets/logo.png)

---

## ✨ Features

- **Interactive Navigation Bar:**
  - **Favorites Counter (Heart):** Tracks bookmarked/liked services.
  - **Coins/Credits System:** Dynamic interactive elements.
  - **Copy Counter:** Real-time feedback showing total copy interactions.

- **Emergency Service Cards:**
  - Clean card design featuring category badges, emergency numbers, and icons.
  - **Favorite/Heart Toggle:** Add or remove services from your favorites list.
  - **Quick Copy:** One-click copy for phone numbers to clipboard with instant user notification.
  - **Direct Call Action:** Simulates emergency call functionality and logs calls to the history panel.

- **Call History Tracker:**
  - Logs recent outbound calls with timestamps.
  - **Clear History:** Option to wipe the recent call log.

- **Fully Responsive Layout:**
  - Tailored experience for desktop, tablet, and mobile devices using Tailwind CSS.

---

## 🛠️ Tech Stack & Technologies Used

- **HTML5:** Semantic structure and content layout.
- **Tailwind CSS:** Utility-first CSS framework for rapid UI design and responsive layouts.
- **JavaScript (ES6+):** Dynamic UI logic, event listeners, state manipulation, and DOM interaction.

---

## 📂 Project Structure

```text
├── assets/
│   ├── heart.png
│   ├── coin.png
│   └── logo.png
├── index.html        # Main HTML entry file
├── index.js          # Main JavaScript file for web functionality
├── tailwind.css      # Custom Tailwind styling & utility imports
└── README.md         # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to run the project locally on your machine:

### Prerequisites
- A modern web browser (Google Chrome, Firefox, Edge, Safari).
- An editor like [VS Code](https://code.visualstudio.com/) with Live Server installed (optional).

### Installation & Local Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/emergency-service-directory.git
   ```
2. **Navigate into the project directory:**
   ```bash
   cd emergency-service-directory
   ```
3. **Open the project:**
   Simply double-click `index.html` or run it using **VS Code Live Server**.

---

## 💡 How It Works

1. **Copying Numbers:** Click the **Copy** button on any emergency card to copy the service number to your clipboard. The copy counter in the top navbar increments automatically.
2. **Bookmarking:** Click the heart icon on any card to increment your favorite counter.
3. **Placing Calls:** Clicking **Call** adds a timestamped record to the **Call History** sidebar on the right side.
4. **Clearing Logs:** Use the green **Clear** button in the Call History section to clear recent call records.

---

## 📜 License

This project is created for educational and community service purposes. Feel free to use and customize it!
