# 🎬 Clustering Students Based on OTT Viewing Preferences  

👨‍💻 Author  
Prasenjit Sasmal  
Year 3, Section 09  
B.Tech CSE (AI-ML)  

---

## 🔍 Project Overview  
The Cultural Committee at SNU is planning the annual Film Fest and wants to understand student audience segments.  
This project applies **Unsupervised Machine Learning (Clustering)** to group students based on:  

- 🎥 Movie Genre Preferences  
- 📺 Series Genre Preferences  
- 🌐 OTT Platform Choices  
- 🗣️ Content Language Preferences  

The insights can help in:  
- Planning screenings that match student interests.  
- Designing theme-based festival nights.  
- Building OTT tie-ups with the right platforms.  

---

## 🛠️ Methodology  

### Data Preprocessing  
- Cleaned and normalized text data.  
- Stripped whitespace and standardized column names.  
- Encoded categorical features using **Label Encoding**.  

### Clustering Approach  
- **Algorithm**: K-Means Clustering  
- **Cluster Range Tested**: k = 2 to 7  
- **Evaluation**:  
  - *Inertia (Elbow Method)* → to find the elbow point.  
  - *Silhouette Score* → to measure cluster quality.  

### Visualization  
- Used **3D scatter plots (Matplotlib)** to display clusters.  

---

## 📊 Results  
- **Optimal number of clusters (k): 4**  
- **Audience groups identified**:  
  1. Bollywood Lovers  
  2. Regional Content Fans  
  3. Global OTT Enthusiasts  
  4. Mixed-Interest Viewers  
- **Inertia analysis** showed a clear elbow at k=4.  
- **Silhouette Score** indicated moderate separation between groups.  
- **3D visualization** highlighted meaningful audience clusters.  

---

## 🎯 Key Insights  
- Students have **diverse but overlapping OTT preferences**.  
- Clustering helps in **curating film nights** (Bollywood, Regional, Global).  
- Supports **OTT collaborations** (Netflix, Prime, Hotstar, etc.).  
- Ensures **higher student engagement** at the Film Fest.  

---

## 📂 Repository Contents  
-  Dataset (student survey responses).  
-  Jupyter notebooks (preprocessing, clustering, visualization).    
- `README.md` → Project documentation.  

---
