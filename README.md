# Power-Efficient Routing System for Packet Transfer

This project simulates and visualizes **standard OSPF** and **Green OSPF** routing using Python and Flask. It computes optimal paths based on various network metrics such as **cost**, **latency**, **power consumption**, and **utilization**, and displays them using an interactive web interface.

## 🔧 Features

- Upload a custom network topology in JSON format
- Compute both:
  - Standard OSPF (based on cost)
  - Green OSPF (custom weights for cost, latency, power, and utilization)
- Visualize:
  - Complete network topology
  - Paths for Standard and Green OSPF
- Flask backend + HTML/CSS/JS frontend
- Interactive graphs using vis.js

## 📁 Project Structure

- `app.py` – Flask backend API
- `index.html` – Web UI for input and visualization
- `ospf.py` – Core OSPF and Green OSPF computation logic
- `router.py`, `link.py`, `lsa.py`, `lsdb.py` – Custom classes modeling routers, links, LSAs, and LSDB
- `ospf-style.css` – Styling for the web interface

## 🚀 Getting Started

1. **Install dependencies**:
   ```bash
   pip install flask
