# 📡 How to Download LISS-IV Data from Bhoonidhi Website

This guide explains the step-by-step process to download **LISS-IV** satellite imagery from the [Bhoonidhi Portal](https://bhoonidhi.nrsc.gov.in/).

---

## 📝 Prerequisites

- A valid **Bhoonidhi account**. Register at: [https://bhoonidhi.nrsc.gov.in](https://bhoonidhi.nrsc.gov.in)
- Internet connection
- Basic knowledge of area coordinates or map navigation

---

## 🛰️ What is LISS-IV?

LISS-IV (Linear Imaging Self Scanner-IV) is a high-resolution sensor onboard Indian Remote Sensing satellites like **Resourcesat-2**. It provides 5.8m spatial resolution data in three bands:
- Band 2: Green (0.52–0.59 µm)
- Band 3: Red (0.62–0.68 µm)
- Band 4: NIR (0.77–0.86 µm)

---

## 🛠️ Steps to Download LISS-IV Data

### 1. **Login**
Go to: [https://bhoonidhi.nrsc.gov.in](https://bhoonidhi.nrsc.gov.in)  
Click **Login** at the top right corner and enter your credentials.

---

### 2. **Open Data Discovery**
- After login, click on **Data Discovery & Download** from the dashboard.

---

### 3. **Select AOI (Area of Interest)**
There are three ways to mark your area:
- **Draw AOI**: Use the map to draw a polygon
- **Upload KML/GeoJSON**
- **Enter Coordinates**: Manually input lat/lon bounding box

---

### 4. **Select Data Parameters**
- **Sensor**: Choose `LISS IV Mono` or `LISS IV Mx`
- **Satellite**: e.g., `Resourcesat-2`, `Resourcesat-2A`
- **Date Range**: Choose required time span
- **Cloud Cover**: (Optional) Set maximum % cloud cover

---

### 5. **Search & Filter Results**
- Click **Search**  
- You’ll see the list of available scenes
- Use the **thumbnail preview** or **metadata** to verify the image quality and coverage

---

### 6. **Add to Cart**
- Click **Add to Cart** for desired scenes
- Go to the **Cart tab**, verify selected items

---

### 7. **Place Order**
- Click **Submit Order**
- Select product type (GeoTIFF is common)
- Confirm and submit

---

### 8. **Download Data**
- Wait for processing (usually 30 minutes to few hours)
- Go to **My Orders**
- Once ready, click **Download**

---

## 💡 Tips

- Always check **cloud cover** before ordering
- Use the **scene footprint** overlay to verify area coverage
- Prefer recent images with low cloud for clear analysis

---

## 🧰 Output Format

Downloaded data will be in `.tif` format and typically includes:
- One file per band (e.g., BAND2.tif, BAND3.tif, BAND4.tif)
- Metadata in `.xml` or `.txt`

---

## 📂 Suggested Folder Structure

```bash
LISS_IV_Data/
│
├── 2024_05_10/
    ├── BAND2.tif
    ├── BAND3.tif
    ├── BAND4.tif
    └── metadata.xml


