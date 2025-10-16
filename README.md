# 🌍 Amhara REDD+ Summary Dashboard (AR, ANR, PFM)

This repository hosts an interactive, browser-based dashboard that visualizes **Afforestation/Reforestation (AR)**, **Assisted Natural Regeneration (ANR)**, and **Participatory Forest Management (PFM)** activities under the **Amhara REDD+ Program**.

The dashboard enables users to upload project data (in CSV format), automatically compute totals, visualize them in charts and maps, and share results online.

---

## 🚀 Features

✅ **CSV Upload & Auto Analysis**  
Upload REDD+ activity data and automatically calculate AR, ANR, and PFM total areas.

✅ **Dynamic KPIs**  
Displays total area achieved (in hectares) for each intervention type.

✅ **Interactive Charts (Chart.js)**  
Visualize performance using **bar** and **pie** charts.

✅ **Interactive Map (Leaflet)**  
Plots REDD+ sites by coordinates and displays detailed popups with region, woreda, activity type, and area.

✅ **Data Table Preview**  
Shows a scrollable table preview of uploaded data for quick inspection.

✅ **Share Buttons**  
Quickly share dashboard results via:
- 📧 Email  
- 🔗 LinkedIn  
- 💬 Telegram

✅ **Fully Client-Side**  
Runs entirely in your browser — no server setup needed.

---

## 🧰 Technologies Used

| Technology | Purpose |
|-------------|----------|
| **HTML5 / CSS3 / JavaScript** | Frontend structure and styling |
| **Bootstrap 5** | Responsive design and layout |
| **Leaflet.js** | Interactive mapping |
| **Chart.js** | Bar and pie chart visualization |
| **PapaParse.js** | CSV parsing and data extraction |

---

## 📊 Input Data Format

The dashboard reads a CSV file with the following **expected column headers**:

| Column | Description |
|---------|--------------|
| `region` | Name of the region (e.g., Amhara) |
| `wereda` | Woreda or district name |
| `site_name` | REDD+ intervention site name |
| `inttype` | Type of intervention (AR, ANR, PFM) |
| `areaha2d` | Area in hectares |
| `intyearst` | Starting year of intervention |
| `Latitude` | Site latitude coordinate |
| `Longitude` | Site longitude coordinate |

📎 Example:

| region | wereda | site_name | inttype | areaha2d | intyearst | Latitude | Longitude |
|---------|---------|------------|----------|-----------|------------|-----------|------------|
| Amhara | Dera | Abay Forest | AR | 125.6 | 2018 | 11.52 | 37.40 |
| Amhara | Kutaber | Zurea Hills | ANR | 85.2 | 2019 | 11.33 | 39.72 |
| Amhara | Gishrabel | Highland PFM | PFM | 110.8 | 2020 | 10.97 | 37.21 |

---

## ⚙️ How to Use

1. **Clone or Download** this repository.  
   ```bash
   git clone https://github.com/Alixsebhatu1/amhara-redd-web-based-operational-dashboard.git
   
2. Open index.html directly in your browser.
   (No installation or server required)

3. Upload your CSV file using the upload box.

4. The dashboard will:

  Calculate total areas for AR, ANR, and PFM

  Display a bar chart and pie chart

 Plot REDD+ sites on an interactive map

 Show your data in a scrollable table

 Use Share Buttons to send your dashboard link via:

🧑‍💻 Author

Prepared by:
Alixander Sebhatu Gebremariam
Geoinformatic and Climate Resilience analysis
📍 Ethiopia

For inquiries or collaboration:
📧 ledetx2005@mail.com

🔗 LinkedIn Profile: https://www.linkedin.com/in/alixander-sebhatu-569230118/?

📜 License

This project is open-source under the MIT License — feel free to reuse and customize with credit.

🪴 Example Dashboard Screenshot

<img width="1834" height="3317" alt="Merg" src="https://github.com/user-attachments/assets/5aefa509-1130-4b5d-a9cc-9f0f749e9ee2" />


