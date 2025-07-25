# 📊 Habit Tracker Dashboard

[![Excel-Based](https://img.shields.io/badge/Built%20with-Microsoft%20Excel-green)](https://www.microsoft.com/en/excel)
[![Status](https://img.shields.io/badge/Status-Completed-blue)]()
[![License](https://img.shields.io/badge/License-MIT-lightgrey)]()

A powerful and visually interactive **habit tracking dashboard** built entirely using **Microsoft Excel**. This project helps users track daily habits, analyze monthly performance, and monitor year-long trends using intuitive charts and tables.

---

## 📁 Screenshots

<details>
<summary><strong>📸 Dashboard Overview</strong></summary>

- Select habit and month filters
- YES/NO counters
- Donut chart showing percentage success
- Bar chart of all habits in selected month
- Line chart showing habit progress over months

![Dashboard](screenshots/Screenshot-1.png)
</details>

<details>
<summary><strong>📊 Data Sheet - Monthly Habit %</strong></summary>

- Shows each habit’s monthly performance
- Auto-calculated percentages
- Used to feed visual charts

![Data Sheet](screenshots/Screenshot-2.png)
</details>

<details>
<summary><strong>📝 Habit Log - YES/NO Tracker</strong></summary>

- Tracks overall YES and NO counts
- Displays lifetime success %

![Habit List](screenshots/Screenshot-3.png)
</details>

---

## 🧩 Features

- ✅ Dynamic month & habit selection
- 📈 Donut, bar, and line chart visualizations
- 📅 Monthly habit performance table
- 🟢 YES/NO tracking with real-time updates
- 📊 Yearly percentage trend analysis
- 🔁 Automated calculations using Excel formulas

---

## 📚 How It Works

<details>
<summary><strong>1️⃣ Daily Habit Input</strong></summary>

You track whether a habit was done or missed each day. These inputs are stored in the backend (YES/NO), and automatically counted monthly.

</details>

<details>
<summary><strong>2️⃣ Monthly Percent Calculation</strong></summary>

Using Excel formulas, the dashboard calculates the percentage success per habit, per month. These percentages populate the bar and line charts.

</details>

<details>
<summary><strong>3️⃣ Dashboard Visualization</strong></summary>

The dashboard reflects:
- Current month's habit stats
- Success rate (e.g., 75% for Habit 3 in January)
- All-habit comparison
- Full-year trend (e.g., from 75% to 100%)

</details>

---

## 📊 Example — Habit 3 (JAN)

| Metric         | Value   |
|----------------|---------|
| YES            | 3       |
| NO             | 1       |
| Success Rate   | 75%     |
| February+      | 100%    |
| Yearly Trend   | ↑ Steady at 100% after January |

---

## 🛠️ Built With

- [Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel)
- Formulas: `IF`, `COUNTIF`, `% calculations`
- Data Validation (for dropdowns)
- Named Ranges
- Donut Charts, Bar Graphs, Line Charts

---

## 💡 Future Improvements

- 📌 Conditional formatting for <70% performance
- 📝 Monthly Notes per habit
- 📤 Export PDF summaries
- 🕹️ Add goal-setting or reminders

---

## 📎 Use Cases

- 🔁 Habit-building routines
- 📅 Monthly performance reviews
- 📈 Behavior change monitoring
- ✅ Gamifying self-discipline

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🧠 Contributing

Want to customize this for your own goals? Fork the repo, change the habits list, and start tracking! PRs and suggestions welcome.

---

## 🙋‍♂️ Questions?

Feel free to open an [issue](https://github.com/yourusername/habit-tracker/issues) if you run into any problems or need improvements.

---

