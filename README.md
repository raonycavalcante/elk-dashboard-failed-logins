# ELK Stack Security Dashboard – Failed Login Attempts

## 📌 Overview
This project was built as part of a TryHackMe lab to practice **SOC analysis using the ELK Stack (Elasticsearch, Logstash, Kibana)**.  
The goal was to monitor and visualize suspicious login attempts across multiple countries.

## 🔧 Tools & Technologies
- **Elasticsearch** – data indexing & searching  
- **Logstash** – log ingestion pipeline  
- **Kibana** – dashboard and visualization  
- Dataset: Simulated SSH brute force logs provided by TryHackMe lab  

## 📊 Dashboard Features
- **Failed Username Attempts** – top usernames targeted by brute force attempts  
- **Source Countries** – geographic distribution of login attempts  
- **Source IPs with Timestamps** – detailed view of attack traffic  

## 🖼️ Example Screenshot
<img width="1914" height="904" alt="Screenshot 2025-09-25 151636" src="https://github.com/user-attachments/assets/9b5d3f20-4252-4922-ba9b-b35d51c79721" />


## 📈 Insights
- The username **"Simon"** had the most failed login attempts (274).  
- Majority of traffic originated from the **United States**, followed by **Canada** and **England**.  
- Logs show continuous brute force activity across multiple IPs.  

---
👨‍💻 Author: C. Raony  
📅 Date: September 2025
