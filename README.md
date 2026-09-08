# 🗂️ Pascalogix Structura | Atomic TODO Notebook

A minimalist, fully functional single‑page planner application that combines a **task notebook** with a **weekly planner**.  
Built with vanilla HTML, CSS (Tailwind), and JavaScript – no external dependencies beyond the Tailwind CDN.

---

## ✨ Features

- **Task Management** – Add, select, and remove tasks from the notebook.
- **Drag & Drop** – Drag tasks from the notebook and drop them into any weekly planner slot.
- **Live Totals** – Automatically updates total, completed, and pending task counts.
- **Date Filtering** – Filter tasks by a selected date (date input in the header).
- **Local Storage** – Your entire planner state is saved automatically in your browser.
- **Responsive** – Works on desktop, tablet, and mobile.
- **Clean UI** – Monochrome palette with red accents, readable typography, and smooth interactions.

---

## 🚀 Getting Started

### Installation

1. **Download** the `index.html` file.
2. **Open** it in any modern web browser (Chrome, Firefox, Edge, Safari, etc.).

> No server or build tools required – it's a self‑contained HTML file.

---

## 🎮 Usage

### Add a Task
- Type a task description into the input field next to the **"Add Task"** button and click the button (or press Enter).

### Select a Task
- Click on any task card in the "Notebook" column – it will be highlighted with a red border.

### Remove a Task
- Hover over a task card and click the **×** button that appears in the top‑right corner.

### Schedule a Task (Drag & Drop)
- **Drag** a task card from the notebook and **drop** it into any day slot (Monday–Sunday) in the planner.
- The slot will turn red when you hover over it.
- Once dropped, the task appears in the slot; you can **remove** it from the slot using the same × button.

### Filter by Date
- Use the date input in the header to select a date – tasks in the notebook will be filtered to show only those assigned to that date (if any).

### Totals
- The footer bar shows:
  - **Total tasks** (all tasks)
  - **Completed** (tasks placed in any planner slot)
  - **Pending** (tasks still in the notebook)

---

## 🛠️ Technical Details

- **HTML5** – semantic, accessible structure.
- **CSS** – custom styles plus Tailwind (loaded via CDN).
- **JavaScript (ES6)** – handles all interactivity, drag‑and‑drop, state management, and local storage.
- **Local Storage** – key `plannerState` stores the entire state as JSON.

---

## 📁 File Structure
/
└── index.html # Complete application (HTML + CSS + JS)

text

---

## 📝 Notes

- The application uses **drag and drop API** – works on all modern browsers.
- All data is saved to `localStorage` – refresh the page and your tasks will persist.
- No external libraries are required – everything is vanilla JS.

---

## 🤝 Contributing

This is a standalone tool. If you'd like to suggest improvements, feel free to fork and modify.

---

## 📄 License

MIT – free to use and modify.
