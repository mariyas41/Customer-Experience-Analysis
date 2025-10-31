# ☎️ Customer Call Optimization Dashboard

### 🎯 Objective
The goal of this project is to analyze **customer call patterns**, **agent efficiency**, and **abandon rates** to identify performance bottlenecks and recommend manpower optimization strategies.  
The analysis focuses on reducing the **call abandonment rate** from 29% to below 10% by improving system reliability and planning efficient staffing for upcoming night operations.

---

### 🧰 Tools & Technologies
- **Power BI** – Data modeling, visualization, DAX measures  
- **Power Query** – Data cleaning and transformation  
- **Excel / CSV** – Raw data storage and import  
- **PowerPoint** – Executive presentation of insights  

---

### 📊 Dashboard 
➡️ [Download Power BI Report (.pbix)](https://drive.google.com/yourlinkhere)

![Dashboard Preview](./Reports/8d1772a1-872c-426c-8eb7-a794e557097c.png)

> The one-page dashboard provides a clear, interactive summary of customer calls, agent performance, and system efficiency across time buckets (9 AM – 9 PM).  
> Key metrics include Total Calls, Answered %, Abandoned %, and Average Handling Time.  
> Insights directly guide staffing and system optimization decisions.

---

### 🎞️ Presentation
  
➡️ [Download Presentation (.pptx)](./CUSTOMER.pptx)

---

### 🔍 Project Overview
This project analyzes **23 days of inbound call data (9 AM – 9 PM)** from a customer service center.  
The aim was to identify why **30% of calls were abandoned**, determine whether it was due to system or staffing issues, and plan night-shift staffing for upcoming service expansion.

---

### 🧩 Key Analytical Steps
1. **Data Cleaning (Power Query)**
   - Replaced missing Agent IDs with “Not Applicable”  
   - Added calculated columns: `Time Bucket`, `Weekday`, and `Shift`  
   - Standardized “Call Status” and validated phone numbers  

2. **DAX Measures**
   - `AbandonPct_Agent` → Abandon % by Agent  
   - `UnassignedAbandonPct` → System-level unassigned calls  
   - `RequiredAgents` → Estimated agent count for planned night operations  

3. **Data Visualization**
   - Abandon %, queue time, and total calls by time bucket  
   - Agent-level efficiency and system vs. human issue split  
   - Comparative analysis for potential night shift planning  

---

### 💡 Insights
| Observation | Insight | Impact |
|--------------|----------|---------|
| Data covers 9 AM – 9 PM only | Within this period, ~30% of calls were abandoned | Service gap even during staffed hours |
| Breakdown of abandonment causes | Majority of abandoned calls due to **system/IVR routing errors**, not agent unavailability | Fixing system issues will yield faster improvements than hiring |
| Agent efficiency analysis | Agents maintained strong response rates and low personal abandon % | Confirms workforce productivity; issue lies beyond human performance |
| Planned night-shift expansion | Estimated required agents as **30% of day-time strength (~28 agents)** based on projected volume | Enables cost-efficient night coverage planning |

---

### 🧠 Recommendations
- **Fix System Routing & IVR Errors** – These account for most dropped calls; prioritize before scaling manpower.  
- **Maintain Current Day Staffing Levels** – Agents are performing well during 9–9 operations.  
- **Plan Night Operations Strategically** – Begin with ~28 agents (30% of day capacity) to cover projected night-time load.  
- **Post-Fix Monitoring** – Track abandonment rate after IVR optimization to measure system improvement.  

---

### 🚀 Outcomes
✅ Root cause identified as **system inefficiency**, not manpower shortage.  
✅ Prevented unnecessary hiring — saved operational costs.  
✅ Designed data-driven plan for **night shift rollout** with estimated staffing of 250 agents.  
✅ Expected abandonment rate reduction from **30% → ~10%** after routing fixes and optimized coverage.


---

### 🗂️ Repository Structure

