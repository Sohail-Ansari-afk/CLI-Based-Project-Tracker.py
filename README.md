# 🛠️ Project Time Tracker (Tkinter GUI)

Track your project work time, calculate billing amounts, and export your logs — all in a simple, local GUI app built with Python's `tkinter`.

---

## 🎯 Features

- ➕ Add new projects with hourly rates
- 🕒 Log time entries with start/end time
- 📌 Add optional notes to time entries
- 💵 Automatically calculates billable hours and amounts
- 📋 Displays logs in a dynamic table
- 📤 Export logs to a CSV file
- 📈 Real-time project summary (total hours & billing)

---

## 🧰 Requirements

- Python 3.x
- Uses only built-in libraries (`tkinter`, `csv`, `datetime`)

✅ No need to install anything!

---

## ▶️ How to Run

1. 💾 Save the file as:

```

CLI-Based Project Tracker.py

````

2. Open your terminal or command prompt.

3. 🏃‍♂️ Run the app:

```bash
python "CLI-Based Project Tracker.py"
````

4. 🖥️ A GUI window will open. You're ready to track!

---

## 🚦 How to Use

### ➕ Add a Project

* Enter project name and hourly rate (₹/hour)
* Click **"➕ Add Project"**

### 🕒 Log Time

* Choose a project from the dropdown
* Enter start and end time (24h format: `HH:MM`)
* Optionally add a note
* Click **"🕒 Log Time"**

> Example: `Start: 09:00`, `End: 11:30` → Adds `2.5` hours to the selected project.

### 📋 View Logged Data

* All time entries are shown in the table below
* Includes project name, duration, note, hourly rate, and total bill

### 📈 See Summary

* A text box shows total hours and ₹ billing for each project

### 📤 Export Logs

* Click **"📤 Export to CSV"** to save logs as `project_logs_export.csv`

---

## 📁 Sample Export Output

| Project      | Start | End   | Duration (hrs) | Note       | Hourly Rate | Bill (₹) |
| ------------ | ----- | ----- | -------------- | ---------- | ----------- | -------- |
| Website Dev  | 09:00 | 11:30 | 2.50           | Homepage   | 500         | 1250.00  |
| Blog Writing | 14:00 | 15:15 | 1.25           | Article #1 | 300         | 375.00   |

---

## 💡 Notes

* Time must be in `HH:MM` format ⏰
* End time must be after start time
* All data is stored **in-memory only**, so export regularly to save your work 💾

---

## 👨‍💻 Author

Created with 💙 and Python’s `tkinter` for freelancers, developers, and anyone who bills hourly.

---

Track smarter, bill faster! 🕒📊💸

```
