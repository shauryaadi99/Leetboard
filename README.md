# 📊 LeetCode Question Dashboard

A simple browser-based **:contentReference[oaicite:1]{index=1}** question tracking dashboard built with:

- 🌐 Vanilla :contentReference[oaicite:2]{index=2}  
- 🎨 :contentReference[oaicite:3]{index=3} (via CDN)  
- 📁 :contentReference[oaicite:4]{index=4} for CSV parsing  
- 💾 Browser `localStorage` for saving progress  

No build tools or backend needed — just one HTML file.  
Easily host it using **:contentReference[oaicite:5]{index=5}**.

---

## ✨ Features

- 📤 Upload CSV files of questions  
- 🏢 Set and display company name  
- ✅ Mark questions as done  
- 📝 Add personal notes for each question  
- 💾 All progress is auto-saved to `localStorage`  
- ⚡ Works fully offline after first load  
- ♻️ Reset dashboard anytime  

---

## 🖼 Example CSV Format

Your CSV should have these columns (**case-sensitive**):

| Title       | Difficulty | Frequency | Acceptance Rate | Link                       | Topics               |
|-------------|-------------|-------------|-------------|-------------|-------------|
| Two Sum     | Easy        | High        | 0.48          | https://leetcode.com/...  | Array, Hash Table     |
| ...         | ...          | ...          | ...            | ...                                     | ...                               |

> **Note:** `Acceptance Rate` should be a decimal (e.g. `0.48`) — it will show as `48.00%` in the table.

---

## 🚀 How to Use

### 1. Upload CSV
- Click **“Upload CSV”** and select your questions file.
- The data will be stored in your browser’s `localStorage`.

### 2. Enter Company Name
- Type in the text box to set the company name shown above the table.

### 3. Track Progress
- Mark questions done ✅
- Add notes 📝
- All changes are saved automatically.

### 4. Reset Dashboard
- Click **“Reset Dashboard”** to clear all saved data.

---

## ⚡ Notes
- All data is stored locally in your browser
- Your progress is preserved across refreshes and browser restarts
- If you open the page on a different browser/device, or clear your browser data, you’ll need to upload the CSV again

---

## 📜 License
This project is open source and free to use.  
Feel free to customize it for your own interview prep!
