# 📦 Supply Chain Visibility System with Optimization Analytics

An interactive supply chain analytics platform designed to provide visibility into **inventory, supplier performance, transportation, sales, profitability, and operational efficiency**.

The system combines multiple supply-chain datasets into an interactive analytics dashboard, helping users monitor key business metrics and identify areas that may require operational attention.

---

## 🚀 Project Overview

Supply chain operations involve multiple connected areas such as inventory management, procurement, suppliers, transportation, and product sales.

This project provides a centralized analytics platform that brings these areas together and presents important metrics through interactive dashboards.

The system is designed for an electronics retail scenario with products across categories such as:

* 📱 Smartphones
* ⌚ Smartwatches
* 🎧 Headphones
* 🔌 Accessories

---

## 🎯 Objectives

* Monitor inventory levels and identify low-stock products.
* Analyze product and category performance.
* Evaluate supplier and procurement performance.
* Analyze transportation and delivery operations.
* Track sales, revenue, profit, and orders.
* Identify overstock and inventory-related issues.
* Provide interactive business analytics through dashboards.
* Support data-driven supply-chain decision making.

---

## ✨ Key Features

### 📊 Executive Summary

Provides a centralized view of important supply-chain KPIs, including:

* Sales
* Revenue
* Profit
* Orders
* Delivery performance
* Inventory status
* Supplier performance
* Shipping and transportation metrics

### 📦 Inventory Analytics

* Current stock monitoring
* Safety stock analysis
* Reorder point monitoring
* Maximum capacity analysis
* Low-stock identification
* Overstock analysis
* Inventory value analysis
* Product-level inventory insights

### 🏭 Supplier & Procurement Analytics

* Supplier performance analysis
* Procurement metrics
* Supplier order analysis
* Purchase-related KPIs
* Supplier comparison
* Order quantity analysis

### 🚚 Transportation Analytics

* Shipment analysis
* Delivery performance
* Transportation metrics
* Shipping cost analysis
* Carrier/transport performance
* Delivery status monitoring

### 💰 Sales & Profitability Analytics

* Sales analysis
* Revenue tracking
* Profit analysis
* Product performance
* Category-level analysis
* Order monitoring

### 📈 Interactive Visualizations

The application uses interactive charts and dashboard components to make supply-chain data easier to explore and understand.

---

## 🧩 Project Milestones

### Milestone 1 — Inventory Analytics

* Inventory KPIs
* Low-stock identification
* Product inventory analysis
* Inventory visualizations
* Stock monitoring

### Milestone 2 — Supplier & Transportation Analytics

* Supplier data analysis
* Procurement metrics
* Transportation analysis
* Supplier-order integration
* Shipping performance analysis

### Milestone 3 — Optimization Analytics

* Inventory turnover analysis
* Overstock identification
* Holding-cost analysis
* Procurement insights
* Transportation efficiency analysis

### Milestone 4 — Executive Summary

* Executive-level KPIs
* Sales and profit overview
* Order and delivery metrics
* Inventory summary
* Supplier summary
* Shipping summary

---

## 🛠️ Technologies Used

| Technology   | Purpose                           |
| ------------ | --------------------------------- |
| Python       | Application and data processing   |
| Streamlit    | Interactive dashboard             |
| Pandas       | Data processing and analysis      |
| Plotly       | Interactive visualizations        |
| CSV          | Dataset storage                   |
| Git & GitHub | Version control and collaboration |

---

## 📁 Project Structure

```text
Supply-chain-visibility-system-with-optimization-analytics/
│
├── app.py
├── generate_data_std.py
│
├── products.csv
├── inventory.csv
├── supplier_orders.csv
├── transportation.csv
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## 📂 Dataset Description

### `products.csv`

Contains product information such as:

* Product ID
* Product name
* Category
* Unit cost
* Selling price

### `inventory.csv`

Contains inventory information such as:

* Product ID
* Current stock
* Safety stock
* Reorder point
* Maximum capacity

### `supplier_orders.csv`

Contains supplier and procurement-related information used for supplier and order analysis.

### `transportation.csv`

Contains transportation and shipment-related information used to analyze delivery and shipping performance.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Ankhitha-05/Supply-chain-visibility-system-with-optimization-analytics.git
```

### 2. Open the project folder

```bash
cd Supply-chain-visibility-system-with-optimization-analytics
```

### 3. Create a virtual environment

Windows:

```bash
python -m venv .venv
```

Activate it:

```bash
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
streamlit run app.py
```

The Streamlit application will open in your browser.

---

## 🔄 Generating the Dataset

The project also includes:

```text
generate_data_std.py
```

This script can be used to generate the project datasets with reproducible random data.

Run:

```bash
python generate_data_std.py
```

The generated CSV files are stored in the project directory.

---

## 📊 Data Processing Workflow

```text
CSV Datasets
     ↓
Data Loading
     ↓
Data Cleaning & Type Conversion
     ↓
Data Integration
     ↓
KPI Calculation
     ↓
Supply Chain Analysis
     ↓
Interactive Visualizations
     ↓
Executive Insights
```

---

## 🏢 Business Scenario

The project represents an electronics retail supply-chain environment where different products are managed across inventory, suppliers, orders, and transportation operations.

The analytics system helps bring these datasets together so users can examine operational metrics from a centralized dashboard.

---

## 🔮 Future Enhancements

Possible future improvements include:

* Machine-learning-based demand forecasting
* Automated inventory-reorder recommendations
* Supplier risk scoring
* Delivery-delay prediction
* Advanced optimization algorithms
* Real-time database integration
* Automated alerts for critical inventory conditions
* Role-based dashboard access
* Cloud deployment
* Advanced predictive analytics

---

## 👩‍💻 Team Project

This project was developed as a collaborative academic project focused on **Supply Chain Visibility and Optimization Analytics**.

### Contributions

The project involved work across:

* Data generation
* Data preprocessing
* Inventory analytics
* Supplier analytics
* Transportation analytics
* KPI development
* Dashboard development
* Optimization analysis
* Executive summary development
* Documentation

---

## 📜 License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

---

## ⭐ Project Repository

**GitHub Repository:**

https://github.com/Ankhitha-05/Supply-chain-visibility-system-with-optimization-analytics
