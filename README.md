# Intel PresentMon Log Analysis

This project analyzes PC performance using logs recorded with **Intel PresentMon**.  
The notebook processes raw PresentMon data into **FPS, CPU, and GPU metrics** and visualizes them over time to highlight stutter, bottlenecks, and performance trends.

I created this notebook as a quick way to **visualize key metrics over the duration of a test**.  
It serves both as a simple performance dashboard and as a **starting point** for working with the most important PresentMon metrics.

---

## Features
- Convert frametime (`MsBetweenPresents`) into **FPS**.
- Compute **average FPS** and **rolling 1% low FPS**.
- Analyze **CPU/GPU utilization** and busy times.
- Use **time-based rolling windows** for cleaner, more representative metrics.
- Generate plots to visualize performance over time.

---

## Repository Structure
- `performance_log_visualizer.ipynb` → Jupyter notebook with the analysis  
- `Logs/` → Sample PresentMon log for testing (csv files)
- `README.md` → project description and usage guide

---

## Requirements
pandas
matplotlib
jupyter

