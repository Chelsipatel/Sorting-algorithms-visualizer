# Sorting Algorithms Visualizer

An interactive React web app that animates how common sorting algorithms work, step by step — built to make abstract algorithms easy to *see*.

🔗 **Live demo:** https://sortingalgosvisualizer.netlify.app/

![demo](./demo.gif)

Built by **Chelsi Patel**.

---

## ✨ What it does
- Visualizes sorting in real time with animated bars.
- Generate a new random array and watch it sort.
- Switch between algorithms from the navigation bar.

## 🧮 Algorithms implemented
- Bubble Sort
- Insertion Sort
- Selection Sort
- Merge Sort
- Quick Sort

## 🛠️ Tech stack
| Layer | Technology |
|-------|------------|
| Framework | React |
| State | React Context API |
| Styling | CSS |
| Tooling | Create React App |
| Hosting | Netlify |

## 🚀 Run it locally
```bash
npm install
npm start
```
Then open **http://localhost:3000**.

## 📂 Structure
```
src/
├── components/
│   ├── algorithms/   # bubble, insertion, selection, merge, quick sort logic
│   ├── Board.js      # renders the array as bars
│   ├── Line.js       # a single bar
│   └── NavBar.js     # algorithm selector
├── containers/
├── context.js        # shared state
└── App.js
```
