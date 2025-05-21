

# 📞 Call Report Dashboard

A responsive, interactive dashboard for visualizing call reports from CSV or JSON files. Built using HTML, JavaScript, and Plotly.js. No server or framework required — just open in a browser!

https://vishnugnath.github.io/call-report-dashboard/
---

## 🔧 Features

- 📊 **Bar Chart** of call outcomes (unique colors).
- 🍩 **Donut Chart** showing lead stages.
- 📈 KPI cards for:
  - Dialled Leads (unique mobile numbers)
  - Total Dials
  - Effective Calls
- 📁 Upload `.csv` or `.json` files directly.
- 🧑‍💼 Filter by user name.
- 📅 Date range filtering.
- 🌗 Dark Mode toggle (with local persistence).
- ⬇️ Download filtered data as CSV.
- 🖼 Download charts as PNG images.
- ✅ Fully client-side — no backend required.

---

## 📂 File Structure

```

├── index.html        # Main dashboard file
├── README.md         # This file

````

---

## 🚀 Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/Vishnugnath/call-report-dashboard.git
cd call-report-dashboard
````

### 2. Open in Browser

Just open `index.html` in any modern browser (Chrome, Firefox, Edge, etc.).

> No server or build step is required!

---

## 📄 Input File Format

Supports `.csv` or `.json` with the following expected columns:

* `User Name`
* `Activity done on (IST)`
* `Call Outcome`
* `Lead Stage`
* `Call Duration` (`hh:mm:ss`)
* `Mobile` or `Phone` or `Phone Number`

---

## 📦 Dependencies

All dependencies are loaded via CDN:

* [Plotly.js](https://plotly.com/javascript/)
* [PapaParse](https://www.papaparse.com/) – for CSV parsing
* [Day.js](https://day.js.org/) – for date handling

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/ac71ad96-bb04-44bb-ae67-1eba2bd87e84)


## 📝 License

MIT License. Feel free to use and modify as needed.

---

## ✨ Author

Made by \Vishnu G Nath
For support or feedback, open an issue or reach out!
