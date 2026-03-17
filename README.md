# 🚚 Flipkart ETA Breach Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing logistics performance using ETA (Estimated Time of Arrival) breach data. The dashboard helps identify delays, vendor performance, and route efficiency across India.

---

## 📊 Key Features

* 📦 Total Trips, On-Time %, Breach %
* 🛣️ Lane-wise Performance Analysis
* 🚛 Vendor-wise Performance Tracking
* 📍 National, Zonal, Local Classification (LZN)
* 📅 Month-wise, Week-wise, Day-wise Trends
* ⏱️ Delay Bucket Analysis (>8 hrs, 4–8 hrs, etc.)
* 🚚 Vehicle Category Insights (B2B, B2C, Myntra, Flipkart)

---

## 🧠 Business Insights

* National routes show higher breach % compared to local routes
* Local deliveries are more stable with lower delays
* Peak breach observed during high-volume weeks (~29%)
* Certain vendors consistently underperform and require optimization

---

## 🏗️ Data Model

* Fact Table: ETA Raw Data
* Dimensions:

  * Calendar Table
  * Vendor Categories
  * Location (Source/Destination)

---

## ⚙️ Key Calculations

* Delay Hours = ATA - Design TAT
* Breach Flag:

  * If ATA > Design TAT → Breach
  * Else → On-Time

---

## 🛠️ Tools Used

* Power BI
* Python
* Excel
* Data Modeling
* DAX

---

## 📸 Dashboard Preview

<img width="1915" height="1078" alt="Screenshot 2026-03-17 194934" src="https://github.com/user-attachments/assets/d986bdc1-ec7f-4b39-aa2a-ffc1e0072c11" />
<img width="1782" height="988" alt="Screenshot 2026-03-17 194337" src="https://github.com/user-attachments/assets/beaed80c-4747-497d-ad1e-d86dd57bd87b" />
<img width="1784" height="986" alt="Screenshot 2026-03-17 194513" src="https://github.com/user-attachments/assets/b7cb3b6e-bbad-4350-9beb-a071a7503e55" />
<img width="1779" height="987" alt="Screenshot 2026-03-17 194535" src="https://github.com/user-attachments/assets/c2c77b70-9532-42e2-a888-9e0a3c6047bd" />
<img width="1915" height="1019" alt="Screenshot 2026-03-17 194613" src="https://github.com/user-attachments/assets/7f1ec4db-fc0d-4faa-84a2-be19cfaf943f" />
<img width="1909" height="1001" alt="Screenshot 2026-03-17 194906" src="https://github.com/user-attachments/assets/58c4c98b-96b9-4e1b-9fa9-73f2862bfb62" />
<img width="1915" height="1078" alt="Screenshot 2026-03-17 194934" src="https://github.com/user-attachments/assets/c6984998-afaa-4fb4-b4b4-e5e471ae3d5d" />


---

## 🚀 Outcome

This dashboard helps logistics teams:

* Reduce delivery delays
* Optimize vendor performance
* Improve route planning
* Enhance customer satisfaction

---

## 👨‍💻 Author

Ranganath Swamy
