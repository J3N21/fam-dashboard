# FAM Compliance Dashboard

This project demonstrates a sample compliance analytics dashboard built using interactive Plotly charts and hosted via GitHub Pages.

The visualizations are designed to showcase a technical approach to tracking and presenting key compliance metrics such as:

- 📊 Compliance Issues by Jurisdiction and Status  
- 🌐 Issue Types by Severity  
- 📅 Compliance Issues Over Time

All dashboards follow a clean, institutional aesthetic aligned with real-world reporting practices in asset management.

---

### 🔍 Data

This demo uses a **dummy dataset (`Dummy_Compliance_Issues_Data.csv`)** generated with the help of ChatGPT to simulate realistic compliance issue tracking for a global investment firm.

The dataset includes fields such as:
- Issue type and severity
- Jurisdiction
- Status (`Open`, `Resolved`, `Escalated`)
- Date opened

---

### 💻 Technical Stack

- Python (`pandas`, `plotly.express`)
- Google Colab for development
- GitHub Pages for hosting
- Clean visual styling inspired by D. E. Shaw’s charting aesthetic

---

### 🌐 Live Demo

Visit the live dashboards (https://j3n21.github.io/fam-dashboard) 

---

### 🚫 Jekyll Disabled

A `.nojekyll` file is included to prevent GitHub Pages from misinterpreting this static site as a Jekyll project.

---

### 📁 Files Included

- `index.html` – main landing page
- `jurisdiction_issues.html` – chart 1
- `issue_severity_sunburst.html` – chart 2
- `issues_over_time.html` – chart 3
- `.nojekyll` – disables Jekyll build
