# **Traffic Accident Analysis Using Python**  

## **📌 Project Overview**  
Traffic accidents are a major public safety concern worldwide, causing loss of life, injuries, and economic damage. This project aims to analyze **traffic accident data** to understand key contributing factors, identify **high-risk locations**, and provide insights that can help policymakers and law enforcement agencies **improve road safety**.  

Using **data analytics and visualization techniques**, we explore how various factors such as **weather conditions, road types, time of day, and urban infrastructure** influence accident severity and frequency. This project leverages **Python, Pandas, Matplotlib, Seaborn, and Geospatial visualization tools** to analyze and visualize accident data.

---

## **🎯 Project Objectives**  
The primary goals of this project are:  
✔️ **Data Exploration** – Understanding the dataset, its attributes, and trends.  
✔️ **Data Cleaning & Preprocessing** – Handling missing values, transforming data types, and preparing for analysis.  
✔️ **Exploratory Data Analysis (EDA)** – Uncovering insights using statistical and graphical methods.  
✔️ **Accident Severity Analysis** – Identifying key factors that contribute to **minor, major, or fatal accidents**.  
✔️ **Impact of External Factors** – Studying how weather, visibility, and road conditions influence accidents.  
✔️ **Time-Based Analysis** – Finding patterns related to the time of day, weekdays vs. weekends, and seasonal variations.  
✔️ **Geospatial Analysis & Accident Hotspots** – Mapping accident locations to detect **high-risk zones**.  
✔️ **Insights & Recommendations** – Drawing conclusions from data to suggest possible improvements in road safety measures.  

---

## **📂 Dataset Description** 
🔗 US Accidents Dataset (Dec 2021) - Kaggle  (https://www.kaggle.com/datasets/diyashmi/us-accidents-dec2021)

The dataset used in this analysis contains **detailed records of traffic accidents** with information such as **location, time, severity, weather conditions, and road attributes**. It helps in assessing risk factors and accident trends.

### **🔹 Key Features of the Dataset**
- **Accident ID** – A unique identifier for each accident.
- **Severity** – Classification of accidents as **Minor, Major, or Fatal**.
- **Start Time & End Time** – Timestamp of when the accident occurred.
- **Latitude & Longitude** – Geographical coordinates of the accident.
- **City & State** – Location where the accident occurred.
- **Weather Condition** – Description of weather conditions at the time of the accident.
- **Temperature (°F)** – The temperature at the time of the accident.
- **Visibility (miles)** – The visibility conditions during the accident.
- **Precipitation (inches)** – Amount of precipitation (rain/snow) recorded.
- **Wind Speed (mph)** – Wind speed during the accident.
- **Sunrise/Sunset** – Whether the accident happened during the **day or night**.

---

## **🛠️ Methodology**  
The analysis follows a structured approach to uncover meaningful insights from the data:

### **🔸 1. Data Collection & Preparation**  
- The dataset is collected from **reliable sources** and loaded into **Python** using **Pandas**.
- Missing and inconsistent data is handled by:
  - Dropping unnecessary columns.
  - Filling or imputing missing values.
  - Converting data types where required.

### **🔸 2. Exploratory Data Analysis (EDA)**  
EDA is performed to **identify patterns, trends, and anomalies**. Key steps include:  
- Understanding **accident frequency and distribution** over time.  
- Checking for **correlations** between weather conditions and accident severity.  
- Visualizing the **impact of road conditions** on accident rates.  
- Analyzing **seasonal trends** (e.g., more accidents in winter due to slippery roads).  

### **🔸 3. Accident Severity Analysis**  
- The data is grouped by **accident severity** to find contributing factors.  
- Weather-based severity is analyzed to determine if **fog, rain, or snow** increase accident risks.  
- Time-based severity trends (e.g., **night vs. day accidents**) are examined.

### **🔸 4. Geospatial Analysis & Hotspot Identification**  
- **Accident locations** are plotted using **geospatial visualization techniques** to identify:  
  - High-risk zones (hotspots).  
  - The most accident-prone **cities and highways**.  
  - Areas where accidents frequently happen under similar conditions.  

---

## **📊 Key Findings & Insights**  

### **1️⃣ Weather Conditions & Accident Severity**
- **Heavy Rain, Fog, and Snow** significantly contribute to accident severity.
- **Low Visibility (<2 miles)** leads to a higher percentage of fatal crashes.
- Accidents **in clear weather** are more frequent but tend to be less severe.

### **2️⃣ Time of Day & Peak Hours**
- **Morning and evening rush hours** show the highest accident rates.
- **Late-night accidents** are often **more severe**, possibly due to overspeeding or low visibility.

### **3️⃣ Seasonal & Monthly Trends**
- Winter months have **more severe accidents** due to **slippery roads** and **foggy conditions**.
- Summer months show **higher accident volumes**, likely due to **increased travel activity**.

### **4️⃣ Geospatial Insights**
- Accident hotspots are concentrated in **urban areas, major highways, and intersections**.
- Certain cities experience more accidents due to **high traffic density** and **poor infrastructure**.
- **Pedestrian-heavy areas** see a higher number of **minor accidents**, whereas highways witness **more severe accidents**.

### **5️⃣ Impact of Road Conditions**
- Accidents **on wet and icy roads** have a higher probability of **severe outcomes**.
- **Potholes, uneven roads, and construction zones** contribute to increased accident risks.

---

## **📌 Recommendations & Actionable Insights**  

Based on the findings, the following recommendations can help improve road safety:  

### ✅ **For Traffic Management Authorities:**  
✔️ Install **better street lighting** in high-risk areas to improve night-time visibility.  
✔️ Implement **variable speed limits** based on **weather conditions** (e.g., reducing speed during rain and fog).  
✔️ Place **warning signs and traffic control measures** in accident-prone areas.  

### ✅ **For City Planners & Policy Makers:**  
✔️ Improve **road infrastructure** to reduce potholes and uneven surfaces.  
✔️ Enforce stricter penalties for **speeding and reckless driving**, especially during peak hours.  
✔️ Increase **public awareness campaigns** about road safety measures.  

### ✅ **For Drivers & Commuters:**  
✔️ Avoid driving in **severe weather conditions** if possible.  
✔️ Maintain **safe distances** between vehicles during **foggy or rainy conditions**.  
✔️ Follow **speed limits** and drive cautiously, especially during **night hours and peak times**.  

---

## **📊 Data Visualization & Insights**  

Here are some key visualizations from the analysis:

### **Accident Severity Distribution**  
![Image](https://github.com/user-attachments/assets/9ef8dc6f-1dd3-47b1-871d-48acca7440a9)

### **Weather Conditions & Accidents**  
![Image](https://github.com/user-attachments/assets/a5d468af-ae4e-4faf-ba55-e08bb9357815)

### **Time-Based Accident Analysis**  
![Image](https://github.com/user-attachments/assets/4a55a177-b45e-4a3f-843f-03520cf3c40d)










---

## **🚀 Conclusion**
This project provides an in-depth analysis of traffic accident data, uncovering key factors that influence accident frequency and severity. By leveraging **data science and visualization techniques**, we can make **data-driven recommendations** to enhance road safety and minimize accidents.  

**Future Scope:**
- Integrating **real-time accident prediction models**.
- Analyzing **driver behavior data** for better insights.
- Using **AI-based risk assessment tools** to suggest **safer driving routes**.

---

## **📩 Contact Information**  
For any queries or collaborations, feel free to reach out:  
📧 **Email**: valaharsh210@gmail.com  
🔗 **LinkedIn**: https://www.linkedin.com/in/vala-harsh

---


