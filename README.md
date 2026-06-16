# ✅ To-Do List App

A clean, minimal to-do list web app built with vanilla HTML, CSS, and JavaScript. Tasks are saved to `localStorage` so they persist across browser sessions.

## 🖼️ Preview

> A styled card UI with a gradient background, task input field, and a list where items can be checked off or deleted.

## 🚀 Features

- **Add tasks** — Type a task and click **Add** (or press Enter) to append it to the list
- **Complete tasks** — Click a task to toggle it as done (strikethrough + checked icon)
- **Delete tasks** — Click the × button on any task to remove it
- **Persistent storage** — All tasks are saved to `localStorage` and restored on next visit

## 🗂️ Project Structure

```
to-do-list/
├── index.html       # App markup and layout
├── style.css        # Styling (gradient background, card UI, task list)
├── script.js        # Task logic (add, toggle, delete, save/load)
└── images/
    ├── icon.png         # App title icon
    ├── checked.png      # Checked task bullet icon
    └── unchecked.png    # Unchecked task bullet icon
```

## 🛠️ Getting Started

No build tools or dependencies required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/machanikki2006-cpu/To-do-List.git
   ```

2. **Open in your browser**
   ```bash
   open index.html
   ```
   Or simply double-click `index.html` in your file explorer.

## 🧰 Built With

- **HTML5** — Semantic markup
- **CSS3** — Flexbox layout, gradient background, custom list styling
- **Vanilla JavaScript** — DOM manipulation, event handling, `localStorage` API
- **Poppins** (Google Fonts) — UI typography

## 📖 How It Works

| Action | How |
|---|---|
| Add a task | Type in the input box → click **Add** |
| Complete a task | Click on the task text to toggle strikethrough |
| Delete a task | Click the **×** icon on the right |
| Data persistence | Tasks are saved to `localStorage` automatically |


