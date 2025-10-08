# GXG Inventory & Analytics System

## 🧩 Overview
**GXG Inventory** is a Python-based desktop system (Tkinter + SQLite + XML + Power BI integration) designed to automate inventory management, sales analytics, and operational reporting for **GXG Store** — a data-driven eCommerce business operating across **eBay** and **Vinted** marketplaces.

Developed to replace manual spreadsheets, the system centralizes stock control, synchronizes pricing, and delivers real-time profitability dashboards integrated with Power BI.

---

## 🚀 Key Features
- 🧾 **Automated Inventory Management:** Add, update, and track products across multiple marketplaces with XML import/export.  
- 📦 **Data Synchronization:** Maintains **1,000+ SKUs** with two-way data sync between eBay and Vinted.  
- 📊 **Business Intelligence Integration:** Power BI dashboards for:
  - Sales performance (revenue, AOV, order growth)
  - Profitability metrics (margin %, CAC, return rate)
  - Supplier and SKU efficiency (lead time, cost, volume)
- ⚙️ **Operational Automation:**
  - Automated database backups  
  - XML/Excel export  
  - Real-time analytics refresh
- 🔐 **Secure Login & Roles:** Admin authentication, hashed passwords, and access control.  
- 💼 **Technology Stack:**
  - Python (Tkinter, pandas, sqlite3, matplotlib)  
  - Power BI (DAX, Power Query)  
  - XML / JSON / Excel for ETL  
  - Packaged via **PyInstaller (.exe)**

---

## 📈 Business KPIs (Jan–Oct 2025)
- **Revenue:** £23,000+ *(projected £30K+ by Dec 2025)*  
- **Profit Margin:** 31%  
- **Orders Growth:** +28% YoY *(2024 → 2025)*  
- **Average Order Value (AOV):** £27.9 → £31.3 *(+12%)*  
- **Transactions:** 420+ YTD *(~42/month)*  
- **Channel Split:** 58% eBay / 42% Vinted  
- **Customer Acquisition Cost (CAC):** £1.90  
- **Return Rate:** 3.5%  
- **SKUs Managed:** 1,000+ active listings  

---

## 🧠 System Architecture
The GXG Store ecosystem connects automation, analytics, and marketplace operations into a unified data flow.  
Its architecture ensures seamless integration between product management, analytics, and external marketplaces — providing real-time performance insights and automated decision-making.

**Key Components**
- **Marketplaces (eBay / Vinted):** Order and inventory data feeds via XML sync  
- **Python Application (Tkinter + SQLite):** Central system handling data validation, stock control, and reporting automation  
- **Power BI Dashboards:** Visualization layer delivering KPIs on sales, profitability, and operations efficiency  
- **Data Storage (SQLite DB):** Local structured storage with automated backups and integrity checks  
- **Integration Layer (XML / API):** Enables synchronization and import/export between all modules  

![GXG Store Architecture](https://github.com/GeorgeMicu2024/GXG-Store/blob/main/gxg_store_architecture.png)

_This design enables continuous data accuracy, reduces manual input by over 70%, and improves decision-making speed by 20%._
