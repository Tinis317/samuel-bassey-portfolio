# We-Ride: Saturday 9 PM Surge Pricing Analysis (Delhi)

> Why does We-Ride charge 1.61x surge on Saturday at 9 PM in Delhi? A supply-demand investigation.

![Project Type](https://img.shields.io/badge/Type-Pricing%20Analytics-blue) ![Domain](https://img.shields.io/badge/Domain-Ride%20Hailing-orange) ![Tools](https://img.shields.io/badge/Tools-Excel%20%7C%20Python-green)

### 🔗 Live Deck
[View Full Presentation (WE-RIDE.pptx)](./WE-RIDE.pptx)

---
### 📌 Business Problem
We-Ride customers are churning due to high surge pricing, especially on Saturday nights in Delhi. The app tells customers "Surge due to high traffic" - but is that true?

**Brief:** Analyze fare, distance, surge multiplier, traffic, time, city & weather to identify the root cause of Saturday 9 PM spike.

### 📊 Dataset
- **Source:** We-Ride internal trip data
- **Key Columns:** Fare, Distance, Surge Multiplier, Traffic Level, Time, Day, City, Active Drivers, Demand-Supply Ratio
- **Missing:** Weather column
- **Focus Window:** Saturday 8-11 PM, Delhi

### 🔍 Methodology
1. Hourly surge analysis (19:00 vs 21:00)
2. City comparison (Delhi vs Mumbai)
3. Correlation analysis (Active Drivers vs Surge)
4. Demand-Supply Ratio modeling
5. Traffic impact validation

### 💡 Key Findings
**1. The Peak Window is Real** - 19:00 = 1.33x, 21:00 = 1.61x (+0.28x jump)

**2. Delhi is Expensive Because of Supply, Not Distance** - Delhi 12.3km 1.55x vs Mumbai 12.8km 1.40x

**3. Driver Shortage = Controllable Surge** - Drivers 10 = 1.71x, Drivers 80 = 1.31x, Correlation -0.62

**4. Demand-Supply Ratio = STRONGEST DRIVER** - Ratio 14.5 on Sat 9 PM Delhi

**5. Traffic is NOT the Villain - Myth Busted** - Low 1.425x vs Jam 1.451x = Only 2% impact

### ✅ Recommendations (With ROI)
**REC 1: ADD DRIVERS** - 35 to 65 drivers, Cost Rs 4500/Sat, ROI 40x

**REC 2: INCENTIVIZE** - Push 7:30 PM + Rs 50 bonus for 3 trips

**REC 3: BUILD TRUST (Cost Rs 0)** - Pre-Book lock 1.2x + Show live drivers

> Closing: We cannot control distance. But we CAN control supply and honesty.

### 📸 Dashboard Preview
<img width="671" height="410" alt="dashboard-overview png" src="https://github.com/user-attachments/assets/197f631f-ad6e-4361-aefd-1f7e624a163e" />
<img width="808" height="420" alt="dashboard-overview png (2)" src="https://github.com/user-attachments/assets/f174ad0b-8a4a-4b8f-9dda-31554c2b3964" />
<img width="872" height="459" alt="dashboard-overview png (3)" src="https://github.com/user-attachments/assets/e87d0eda-0b76-473a-9d27-cffd9cfdd69d" />

### 🛠️ Tools Used
- Excel / Google Sheets
- PowerPoint

### 📁 Files in this Repo
- `WE-RIDE.pptx`
- `README.md`
- `/images`
- https://docs.google.com/presentation/d/1753aoIefCoVw3lYZqpkRRn_gV4zNhTOT/edit?usp=drive_link&ouid=106408375730070531057&rtpof=true&sd=true

### 👤 Author
Samuel Etini Bassey | Junior Data Analyst | Lagos, Nigeria
- LinkedIn: www.linkedin.com/in/samuel-bassey-327b97233
- Email: sbassey999@gmail.com
