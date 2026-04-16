# Linked Lists in C — Interactive Learning App

## 🚀 How to Run

### Option 1: Open directly in browser (Easiest)
1. Unzip the file: `unzip linkedlist_app.zip`
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
   - Double-click the file, OR
   - Drag it into your browser window

No server needed — it's a self-contained HTML file.

---

### Option 2: Local HTTP Server (Recommended for best experience)

**Using Python (most systems have this):**
```bash
# Python 3
cd linkedlist_app
python3 -m http.server 8080

# Python 2 (older systems)
python -m SimpleHTTPServer 8080
```
Then open: http://localhost:8080

**Using Node.js:**
```bash
npx serve .
```

**Using VS Code:**
Install the "Live Server" extension → right-click index.html → "Open with Live Server"

---

## 📦 Contents
```
linkedlist_app/
├── index.html    ← Complete app (single file, all CSS + JS embedded)
└── README.md     ← This file
```

---

## 🗂️ App Sections

| Section | What You'll Learn |
|---------|------------------|
| 📚 **Basics** | Pointers, struct Node, heap vs stack, malloc/free |
| ⚙️ **Operations** | Animated insert, delete, traverse, search |
| 🧮 **Algorithms** | Reverse, Find Middle, Detect Cycle, Palindrome, Odd-Even |
| 💼 **Interview Prep** | 5 classic problems with C code and common mistakes |
| 🐛 **Debug Mode** | Segfaults, memory leaks, dangling pointers — visualized |
| 🎯 **Quiz** | 10 MCQs to test your understanding |

---

## 🌙 Features
- Dark / Light mode toggle (bottom of sidebar)
- Step-by-step animated operations with speed control
- C code with syntax highlighting + copy button
- Memory address simulation (0x100, 0x110...)
- Color-coded node states: Blue=Normal, Yellow=Current, Green=Processed, Red=Modified
- Interactive linked list you can build and manipulate

---

## 🔧 Technical Details
- Pure HTML + CSS + JavaScript (no frameworks, no backend)
- SVG-based visualization engine
- Works offline
- Tested on Chrome 120+, Firefox 120+, Edge 120+

---

## 💡 Tips for Learners
1. Start with **Basics → Pointers** tab before jumping to Operations
2. In **Operations**, try building a list with Insert, then watch Traverse animate it
3. In **Algorithms**, press ▶ and slow down the speed slider to follow each step
4. Read the **Debug Mode** scenarios — they cover the #1 interview pitfall questions
5. Take the **Quiz** at the end to validate your understanding
