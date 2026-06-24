# FTMO NAS100 Calculator + Journal

A comprehensive, self-contained web application designed for traders to calculate position sizes, track compliance with FTMO rules, and maintain a trade journal. This tool helps traders manage risk, ensure compliance with FTMO trading objectives, and log trades with screenshots and notes.

---

## 📌 Features

### Position Sizing Calculator
- **Live Calculation**: Dynamically computes lot size based on account balance, risk per trade, entry, stop loss, and take profit prices.
- **Risk Management**: Visualizes risk in dollars, risk-reward ratio, and win rate required for profitability.
- **FTMO Compliance**: Checks against FTMO trading objectives (e.g., max daily loss, max total loss, risk-reward ratio, minimum trading days).
- **Forbidden Practices**: Flags violations like trading during high-impact news, holding overnight (for standard accounts), or using EAs.

### Trade Journal
- **Trade Logging**: Records trade details (entry, SL, TP, lot size, P&L, notes, screenshots).
- **Search & Filter**: Allows filtering by result (win/loss/breakeven), direction (long/short), and date.
- **Statistics Dashboard**: Displays win rate, net P&L, average R:R, largest win/loss, and more.
- **Image Support**: Supports uploading and storing trade screenshots.

### High-Impact News Calendar
- **2026 Calendar Data**: Preloaded with major economic events (NFP, CPI, FOMC, central bank decisions).
- **Filtering**: Filter by impact level (High/Medium) and navigate by week.
- **Today’s Events**: Highlights high-impact events for the current day.

### UI/UX Design
- **Dark Theme**: Professional, modern design with a dark color scheme.
- **Responsive Layout**: Adapts to mobile and desktop screens.
- **Interactive Elements**: Sliders, toggles, and dropdowns for easy input.

---

## 🚀 How to Use

### Local Usage
1. **Download the `index.html` file** from this repository.
2. **Open it in a browser** (Chrome, Firefox, Edge recommended).
3. The tool will work offline after the first load (all data is stored locally in IndexedDB or localStorage).

### Hosting on GitHub Pages
1. **Fork this repository** or create a new one.
2. **Upload the `index.html` file** to the root of your repository.
3. **Enable GitHub Pages** in the repository settings (select `main` branch and `/root` folder).
4. Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`.

### Hosting on a Web Server
- Upload the `index.html` file to any web server (e.g., Netlify, Vercel, or a local server like `python -m http.server`).

---

## 📂 Project Structure
```
ftmo-calculator/
├── index.html          # Main application file
└── README.md           # Project documentation
```

---

## 🛠 Technologies Used
- **HTML5/CSS3**: Structure and styling.
- **JavaScript (ES6+)**: Logic, DOM manipulation, and storage.
- **IndexedDB**: Primary storage for trades and images (handles large data).
- **LocalStorage**: Fallback storage if IndexedDB is unavailable.

---

## 📝 Notes
- **No External Dependencies**: Pure HTML/CSS/JavaScript. No libraries or frameworks required.
- **Data Persistence**: Uses IndexedDB (or localStorage fallback) to store trades and images locally in your browser.
- **Sandbox Limitation**: If running in a sandboxed environment (e.g., some online code editors), storage may not persist. Use a local browser or hosted environment for full functionality.

---

## 🤝 Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
