# Performance-Metrics
Interactive demo site for INFO 5200 – Information Organization. Visualizes performance metrics (accuracy, efficiency, errors, participation, final grades) using sample data and interactive charts. Built with Chart.js and Papa Parse, hosted on GitHub Pages.

# INFO 5200 – Performance Metrics Demo

This repository contains an **interactive website** that demonstrates how performance metrics can be tracked and visualized in an educational context.  
It was created for a class presentation in **INFO 5200 – Information Organization**.

## 🔍 Features
- Interactive **week filter** to view changes over time  
- **KPIs** for average accuracy, time, errors, and participation  
- **Bar charts** for accuracy, efficiency, and error counts  
- **Scatter plot** showing participation vs final grades (bubble size = accuracy)  
- Fully browser-based (no backend required)

## 📂 Data
Sample dataset: [`public/performance_metrics_sample.csv`](public/performance_metrics_sample.csv)  
Columns:
- `Student`
- `Week`
- `Assignment Accuracy %`
- `Time Taken (min)`
- `Errors`
- `Participation Score`
- `Final Grade`

## 🚀 Usage
1. Clone the repo or download the ZIP.
2. Open `index.html` in your browser.
3. Use the **Week selector** to filter results.
4. Interact with the charts live.

## 🌐 Live Demo
Once deployed with GitHub Pages, the site will be available at:  
`https://<your-username>.github.io/<repo-name>/`

## 🛠️ Built With
- [Chart.js](https://www.chartjs.org/) – for data visualization  
- [Papa Parse](https://www.papaparse.com/) – for CSV parsing  

---

