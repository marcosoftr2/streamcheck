# 📡 StreamCheck by rojixlab
**A sleek, real-time web tool to measure internet speed and video streaming readiness.**

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Author](https://img.shields.io/badge/author-rojixlab-orange.svg)

---

## 🚀 Overview
**StreamCheck** is a lightweight, high-performance speed test designed specifically to help users understand their connection's capability for different video qualities, from standard definition (SD) to 4K Ultra HD.

### Key Features:
* **Real-time Tracking:** Visualizes download speeds instantly using Chart.js.
* **Streaming Readiness:** Automatically categorizes your connection (SD, HD, 2K, 4K).
* **Modern UI:** Dark mode aesthetic with a mobile-responsive design.
* **No Overhead:** Built with pure HTML, CSS, and Vanilla JavaScript.

---

## 🛠️ Built With
* **HTML5 & CSS3:** For a responsive and modern layout.
* **JavaScript (ES6+):** Real-time data processing via Fetch API Streams.
* **[Chart.js](https://www.chartjs.org/):** Dynamic data visualization.

---

## 💻 How it Works
The tool fetches a high-resolution sample file from a CDN and measures the transfer rate bit by bit. This provides a more accurate representation of sustained download speeds compared to simple ping tests.

| Speed (Mbps) | Recommended Quality |
| :--- | :--- |
| **< 5** | SD Quality (480p) |
| **5 - 15** | HD Quality (1080p) |
| **15 - 25** | 2K / Super HD |
| **> 25** | 4K Ultra HD |

---

## ☕ Support the Project
If you find this tool useful, consider supporting the development of more free tools!

[![Support on Ko-fi](https://img.shields.io/badge/Support%20on%20Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/rojixlab)

---

## 📄 License
This project is open-source and available under the **MIT License**.

Developed with ❤️ by **rojixlab**.
