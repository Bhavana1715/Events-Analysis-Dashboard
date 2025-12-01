
# ✨ **The Engagement Equation: What Makes Events Successful in India?**

## 💠 **Project Overview**

* Events across India—from entertainment shows to business summits—have grown significantly over the last **8 years**, attracting audiences from diverse cities, categories, and formats.

* With rising investments, evolving attendee expectations, and a surge in hybrid/virtual formats, understanding event success requires deep analysis of **attendance, profit, ratings, ROI, organizers, locations, and engagement factors**.

* This analysis explores **9,964 events** from 2017–2025, covering every detail: registrations, attendance, ticket pricing, organizer investments, categories, formats, food availability, seating capacity, and more—as outlined in the hackathon dataset. 

* The goal is to uncover **what truly makes an event successful in India** and provide **actionable, data-driven recommendations** to improve profitability, engagement, and audience satisfaction.

---

## 💠 **Data Source / Dataset**

The dataset is provided as part of the **KSR Datavizon Event Management Hackathon**, consisting of a structured star-schema model with **one fact table** and **five dimension tables**. 

### ➽ **Tables Included**

### **📌 Events_Data_fct (Fact Table)**

Contains all major event metrics:

* Event_ID (Primary Key)
* Event Name, Event_Date
* Seating Capacity
* Ticket Selling Price (INR)
* Organizer Investment per Ticket (INR)
* Duration (Hours)
* No. of Registrations
* Attended People
* Topics Demonstrated
* Event Type (Paid / Free)
* Lunch/Snacks Provided
* Attendees’ Rating (Out of 5)
* Event Format (In-Person, Virtual, Hybrid)
* Foreign keys → Category, City, State, Organizer, Venue

### **📌 Category_dim**

* Category_key
* Category (Arts, Technology, Business, Sports, Entertainment, etc.)

### **📌 City_dim**

* City_key
* City

### **📌 State_dim**

* State_key
* State

### **📌 Organizer_dim**

* Organizer_key
* Organizer

### **📌 Venue_dim**

* Venue_key
* Venue

The dataset enables deep exploration of trends, profitability, organizers’ efficiency, category performance, seating utilization, and geographic insights across India.

---

## 💠 **Tools Used**

🧹 **Pandas**, **NumPy** — Data Cleaning & Pre-processing

📊 **Power BI** — Power Query, Data Modeling, DAX Measures, Dashboard Creation

📝 **GitHub** — Documentation & Version Control

---

# ✨ **Key Insights & Findings**

Below insights are directly derived from your Event Management Dashboard PDF.

---

## ⭐ **Key Performance Indicators (KPIs)**

* **Total Events:** 9,964
* **Total Registrations:** 537K
* **Total Attendees:** 486K
* **Attendance Rate:** 🌟 **90.35%**
* **No-Show Rate:** 9.65%

These numbers indicate strong interest, high turnout, and effective event execution across India.

---

## ⭐ **Annual Registrations & Attendance (2017–2025)**


![a](https://github.com/user-attachments/assets/56d70315-3155-479e-bf84-afd723d5123a)




* Registrations range between **62K–68K** annually.
* Attendance closely follows registrations, proving consistent audience conversion.
* Even during fluctuating years, engagement remains steady—suggesting strong market demand.

---

## ⭐ **Monthly Engagement Trends**

![bb](https://github.com/user-attachments/assets/d1f35ced-4447-4ac7-b5d3-5efa0fd5e668)



* Peak months: **January, May, July, August**
* Dip in **December**, likely due to holidays.
* Attendance patterns mirror registration curves across all months.

---

## ⭐ **Event Format Performance (Hybrid vs In-Person vs Virtual)**



![cc](https://github.com/user-attachments/assets/c04009f0-e95a-43a9-ba4b-365c12550118)


* **In-Person Events** → Highest attendance & ratings
* **Hybrid Events** → Balanced performance with strong profitability
* **Virtual Events** → Lower attendance but cost-efficient

In-person experiences remain dominant in India’s event landscape.

---

## ⭐ **Attendance by City**


![ddd](https://github.com/user-attachments/assets/3156cc2e-a5b6-4ff9-9819-ca5a666aeec3)

Top cities by attendance:
🌟 **Chennai**
🌟 **Coimbatore**
🌟 **Bengaluru**
🌟 **Hyderabad**
🌟 **Goa**

Southern India leads both in frequency and turnout.

---

# 💰 **Profitability & ROI Insights**

## ⭐ **ROI (%) by Category**

![ff](https://github.com/user-attachments/assets/1c8d3106-2c29-4f9f-95db-5fda94ac3ad5)


🥇 **Arts** – 68%
🥈 **Food** – 65%
🥉 **Entertainment** – 65%
🎬 **Film** – 64%
🏅 **Sports** – 63%
⚠️ **Literature** – −100% (lowest ROI)

Categories like Arts, Entertainment, Film, and Food deliver maximum returns.

---

## ⭐ **Category-Wise Profit Breakdown**

![ii](https://github.com/user-attachments/assets/780b0cd2-1a44-4cb3-8c8f-c194b15cba68)


* **Business:** 28M (22.7%)
* **Technology:** 25M (20.7%)
* **Entertainment:** 19M
* **Food:** 17M
* **Sports:** 12M
* Others contribute smaller margins

Business & Technology together form nearly **45% of total profits**.

---

## ⭐ **Investment vs Revenue (Yearly)**


![uu](https://github.com/user-attachments/assets/d795af94-6258-4526-a877-e4ff788a4870)

* Revenue consistently exceeds investment across all years.
* Overall ROI: 🌟 **53.77%**
* **Total Revenue:** 325M
* **Total Investment:** 205.85M
* **Total Profit:** 119M

---

## ⭐ **ROI by City & State**

📍 Page 3 graph: 

Cities with highest ROI (71–75%):
🔹 Dehradun
🔹 Mysuru
🔹 Vadodara
🔹 Gurgaon
🔹 Kochi
🔹 Kozhikode
🔹 Vijayawada

---

# 🤝 **Engagement, Experience & Success Factors**

## ⭐ **Top 10 Highest-Rated Events**

📍 Page 4 list :

Highest-rated events (4.5–4.8 stars):
🍳 International Cooking
🧁 Baking Masterclass
🧘 Yoga & Sports Conference
🍽️ Gourmet Food Tasting
🎯 Team Building
🏀 Basketball Clinic
📈 Financial Planning Meet
🏏 Local Cricket Tournament
👨‍💼 Project Management Workshop

---

## ⭐ **Top Event-Hosting States & Cities**

📍 Page 4 bar charts :

### **States**

1. Tamil Nadu – 1,166 events
2. Karnataka – 883
3. Kerala – 728
4. Gujarat – 718
5. Maharashtra – 716

### **Cities**

1. Chennai – 510
2. Coimbatore – 431
3. Bengaluru – 389
4. Hyderabad – 271
5. Goa – 263

---

## ⭐ **Top Organizers**

📍 Page 4 organizer ranking :

✨ AppDevGuild
✨ DigiMarkPro
✨ ProjectFlow
✨ SoundCanvas
✨ TechSkills

DigiMarkPro leads with highest total profit (~11.9M).

---

## ⭐ **Food Availability vs Attendance**

📍 Pie chart on page 4 :

* **With Snacks/Lunch:** 389K attendees (80.06%)
* **Without Food:** 97K attendees (19.94%)

Food dramatically improves turnout & satisfaction.

---

## ⭐ **Seating Capacity Insights**

📍 Page 4 scatter plot reveals:

* Best outcomes when seating is between **100–150 seats**.
* Both registrations and attendees increase within this range.

---

## ⭐ **Weekday vs Weekend Events**

📍 Page 5 stats :

* **Weekdays:** 71.47% events (more successful)
* **Weekends:** 28.53%

Weekdays are the preferred hosting choice.

---

# 💠 **Recommendations**

Based on combined findings and the “Winning Equation” shown on **page 5** of your PDF: 

### ✅ **Ideal Event Duration:** 3–4 hours

### ✅ **Offer Snacks & Lunch** – boosts ratings & attendance

### ✅ **Ticket Price Range:** ₹300–₹400

### ✅ **Seating Capacity:** 100–150 seats

### ✅ **Prefer In-Person Events** → highest engagement

### ✅ **Hybrid as second-best option**

### ✅ **Focus on Entertainment & Technology** → best ROI & ratings

### ✅ **Choose Metro Cities (Bengaluru, Ahmedabad)** → strong ROI

### ✅ **Collaborate with High-Performing Organizers**

### ✅ **Host events on Weekdays** → higher success probability


