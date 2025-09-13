📊 LeetCode Question Dashboard

A simple browser-based LeetCode question tracking dashboard built with:

🌐 Vanilla JavaScript

🎨 Tailwind CSS (via CDN)

📁 PapaParse for CSV parsing

💾 Browser localStorage for saving progress

No build tools or backend needed — just one HTML file.
Easily host it using GitHub Pages.

✨ Features

📤 Upload CSV files of questions

🏢 Set and display company name

✅ Mark questions as done

📝 Add personal notes for each question

💾 All progress is auto-saved to localStorage

⚡ Works fully offline after first load

♻️ Reset dashboard anytime

🖼 Example CSV Format

Your CSV should have these columns (case-sensitive):

Title	Difficulty	Frequency	Acceptance Rate	Link	Topics
Two Sum	Easy	High	0.48	https://leetcode.com/
...	Array, Hash Table
...	...	...	...	...	...

Acceptance Rate should be a decimal (e.g. 0.48) — it will show as 48.00% in the table.

🚀 How to Use

Upload CSV

Click “Upload CSV” and select your questions file.

The data will be stored in your browser’s localStorage.

Enter Company Name

Type in the text box to set the company name shown above the table.

Track Progress

Mark questions done ✅

Add notes 📝

All changes are saved automatically.

Reset Dashboard

Click “Reset Dashboard” to clear all saved data.

🌐 Hosting on GitHub Pages

Create a new repository

Add the single index.html file to the repo root

Go to Settings → Pages

Under Build and deployment, choose:

Source: Deploy from branch

Branch: main → / (root)

Click Save

Your site will be available at
https://<your-username>.github.io/<repo-name>/

⚠️ Notes

All data is stored locally in the browser via localStorage

Your progress is preserved on refresh and browser restarts

If you open the page on a different browser/device, or clear your browser data, you’ll need to upload the CSV again

📜 License

This project is open source and free to use.
Feel free to customize it for your own interview prep!
