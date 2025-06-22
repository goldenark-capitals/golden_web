# GoldenArk Capitals Website

## 🚀 Project Overview

GoldenArk Capitals is a cutting-edge investment firm that leverages **advanced AI trading systems and automated investment strategies** to maximize portfolio returns. This repository contains the source code for the GoldenArk Capitals website, designed to showcase our mission, products, and performance to potential clients.

The website's homepage features a dynamic "Weekly Trading Report" dashboard. This live dashboard automatically fetches and displays trade data and key summary statistics from CSV files, updating periodically to reflect the latest information.

## ✨ Features

* **Dynamic Trading Report**: Displays a live, automatically updating "Weekly Trading Report" on the homepage, populated from `trading.csv` and `report.csv`.

* **Automatic Data Refresh**: The frontend periodically re-fetches data from the backend, ensuring the trading report reflects any additions or changes in the CSV data.

* **Sliding Table Rows**: The trade analysis table transitions through groups of 6 rows, providing a dynamic view of trade history.

* **Pause on Interaction**: The automatic row transition pauses when a user hovers over the table (desktop) or touches it (mobile), resuming when interaction ends.

* **Conditional Styling for Metrics**: "Week Profit" and "Avg Trade" values are styled with green for positive performance and red for negative. "Win Rate" is colored yellow for 'Win' and red for 'Loss'.

* **Responsive Design**: Built using Tailwind CSS, ensuring optimal viewing and interaction across various devices and screen sizes.

* **Clear Navigation**: Provides intuitive navigation to different sections of the website, including a mobile-friendly menu.

* **Scroll Animations**: Integrates AOS (Animate On Scroll) for engaging content transitions as the user scrolls.

## ⚙️ Technologies Used

* **Backend**: Python 3.x, Flask, Pandas (for CSV processing)

* **Frontend**: HTML5, JavaScript (ES6+), Tailwind CSS, AOS (Animate On Scroll)

* **Deployment**: Configured for deployment on Render (using Gunicorn)

* **Data Storage**: CSV files (`static/trading.csv`, `static/report.csv`)