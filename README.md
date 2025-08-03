# 🌐 Credly Badge Web Scraper

A powerful and easy-to-use Python tool to **scrape badge details** from any public [Credly](https://www.credly.com) profile.  
This project is perfect for exporting your earned certifications into a structured format.

---

## ✨ Features
- ✅ Extracts all badges from a public Credly profile
- ✅ Collects:
  - 🏆 **Badge Name**
  - 🔗 **Badge URL**
- ✅ Handles infinite scrolling to ensure all badges are loaded
- ✅ Works seamlessly on **Google Colab** and **local machines**
- ✅ Saves output as a **CSV file**

---

## ⚙️ Installation

### 🔹 1. Clone this repository
```bash
git clone https://github.com/rk98991439/web_scarping
cd web_scarping
````

### 🔹 2. Install Dependencies

```bash
pip install selenium webdriver-manager beautifulsoup4
```

> ✅ On **Google Colab**, required packages and ChromeDriver installation are handled automatically by the notebook.

---

## ▶️ Usage

### ✅ Option 1: Google Colab (Recommended)

1. Open `credly_WEB_spaping.ipynb` in Google Colab.
2. Update the profile URL in the script:

   ```python
   url = "https://www.credly.com/users/your-username/badges#credly"
   ```
3. Run all cells and download your badge data as a CSV file.

---

### ✅ Option 2: Run Locally

1. Make sure Google Chrome is installed.
2. Run the script:

   ```bash
   python credly_scraper.py
   ```
3. Your badge details will be saved to `credly_badges.csv`.

---

## 📤 Output Format

The scraper outputs a **tab-separated CSV** file with badge names and their URLs:

```
name    url
"Generative AI Essentials"    "https://www.credly.com/badges/088c28ae-9e57-427e-8a3e-adb439d59a40"
"Containers & Kubernetes Essentials"    "https://www.credly.com/badges/d84a7abb-4d49-49d8-bece-58e956a6233e"
```

---


## 🚀 Roadmap

* [ ] Add **Issuer Name** (e.g., Coursera, AWS)
* [ ] Add **Issue Date** and **Badge Image**
* [ ] Export to **JSON** and **Excel**
* [ ] Add CLI arguments for automation

---

## 👤 Author

**Rohit Kumar**
🔗 [LinkedIn](https://www.linkedin.com/in/rohit--kumar-/)

