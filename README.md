# Spotify Streaming Analytics 🎧📈

This repository contains the complete project for **Spotify Streaming Analytics** developed as part of the **Lab Project work for Big Data Analytics (Semester VI)**.

The repository is centered around analyzing the **Top 200** and **Viral 50** Spotify charts across the years **2019, 2020, and 2021**, uncovering deep insights into music consumption patterns, top artists, top songs, regional engagement, chart trends, and global listening habits, through **data analysis and visualization using R programming language**.

Below, point-by-point complete detailed information is discussed.

---

## Chapter 1: Introduction

The digital music revolution has changed the way we listen to and consume music globally. Platforms like **Spotify** have become dominant forces in the entertainment industry, influencing listener behavior, artist strategies, and music trends.

The **Spotify Streaming Analytics** project was developed to analyze **global daily streaming charts** to discover patterns, trends, and insights from millions of records. The data collected spans three significant years (2019–2021), covering the pre-pandemic, during pandemic, and recovery phases, offering a rich dataset for exploration.

The core idea behind this project was to:

- Understand the **year-over-year growth** in music streaming.  
- Identify **top-performing artists and songs** globally.  
- Analyze **regional differences** in music consumption.  
- Explore **chart dynamics** (new entries, moves up, moves down).  
- Visualize the **global spread** of music streams geographically.

Using the R programming language and its rich ecosystem of packages, the project builds comprehensive, professional-quality plots and dashboards, enabling a clear view of the changing landscape of music streaming.

---

## Chapter 2: Motivation and Problem Statement

### 2.1 Motivation

With the explosive growth of Spotify, billions of streams are generated daily across the world. However, **raw charts** or **summary reports** often fail to reveal deeper patterns such as:

- How does streaming behavior vary across regions?
- What is the typical lifecycle of a new chart entry?
- How did events like the COVID-19 pandemic impact streaming volumes?
- Which countries show the highest per-user streaming activity?

There was a clear need to **systematically explore**, **analyze**, and **visualize** this data to find meaningful insights beyond basic leaderboard statistics.

### 2.2 Problem Statement

> **"To perform comprehensive time-series, categorical, and geospatial analysis on Spotify’s Top 200 and Viral 50 datasets for the years 2019-2021, uncovering trends in music consumption, regional engagement, and chart dynamics, using Big Data Analytics techniques."**

---

## Chapter 3: Objectives and Scope

### 3.1 Objectives

- Analyze **temporal trends** in global music streaming.  
- Identify and rank **top 10 artists** and **top 10 songs** by streams.  
- Explore **regional differences** in total and average streams.  
- Understand **chart movement** patterns (`MOVE_UP`, `NEW_ENTRY`, etc.).  
- Visualize **global engagement** using geospatial maps.
- Derive **meaningful insights** to assist industry stakeholders.

### 3.2 Scope

- Data limited to **Spotify Top 200** and **Viral 50** charts.
- Years covered: **2019–2020–2021**.
- Global perspective covering **all Spotify-supported countries**.
- Analysis performed using **R** and **open-source libraries**.

---

## Chapter 4: Literature Survey

Previous studies on music streaming analytics often focus on **short-term** datasets or **single-region** behavior. 

This project extends the scope by:

- Covering a **three-year timeline**.
- Including **global regional diversity**.
- Using **heatmaps** and **geospatial visualization** for better interpretability.

Key references include Kaggle’s Spotify datasets and academic papers related to **Big Data Analytics in Music Streaming**.

---

## Chapter 5: Software and Hardware Requirements

### 5.1 Developer Environment

- **Language:** R 4.x  
- **IDE:** Google Colab 
- **Packages:** ggplot2, dplyr, tidyr, reshape2, lubridate, maps, mapdata  
- **Data Visualization:** ggplot2, maps  

### 5.2 Minimum System Requirements

- **Processor:** Intel i5 / Ryzen 5 or better  
- **RAM:** 8 GB minimum (recommended 16 GB)  
- **Disk:** SSD preferred (minimum 5 GB free)  
- **Operating System:** Windows 10 / Ubuntu 20.04 or higher  

---

## Chapter 6: Flowchart and Dataflow Diagram

### 6.1 Flowchart Diagram

The project follows a systematic flow:

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Flow%20Chart.png)
---

### 6.2 Dataflow Diagram

The modular structure ensures:
- Efficient memory use
- Reproducibility
- Expandability

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/DFD.png)
---

### 6.3 Sequence Diagram

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Sequence%20Diagram.png)
---

### 6.4 System Overview Diagram

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/System%20Overview.png)

---

## Chapter 7: Data Preprocessing

- **Date Parsing:** Convert string dates to datetime objects.
- **Feature Extraction:** Year, Month columns created.
- **Handling Missing Values:** Dropping rows with critical NAs.
- **Normalization:** Streams expressed in millions for easier visualization.

Each preprocessing step was carefully validated to ensure no loss of data integrity.

---

## Chapter 8: Implementation and Scripts

| Script Name                  | Purpose                                                      |
|-------------------------------|--------------------------------------------------------------|
| `01_preprocessing.R`          | Cleaning and preparing datasets                             |
| `02_eda_total_streams.R`      | Total streams EDA and plots                                 |
| `03_top_artists_songs.R`      | Analysis of top artists and songs                           |
| `04_regional_analysis.R`      | Regional analysis and heatmap generation                    |
| `05_trend_analysis.R`         | Chart dynamics trend study                                  |
| `06_geospatial_map.R`         | World map plotting of total streams                         |

---

## Chapter 9: Output Snapshots and Graphs

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20144849.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20144945.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20145117.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20145211.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20145250.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20145345.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20145424.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20145458.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20145543.png)
---

![](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/2.%20Rough%20Work%20%26%20Data/Screenshot%202024-10-20%20145622.png)

---

## Chapter 10: Results & Observations

- **2020 saw a surge** in global streams, likely due to COVID lockdowns.  
- **Drake** topped artist streaming charts across multiple regions.  
- **Regional variation:** Europe and Latin America had unique musical preferences compared to North America.  
- **New chart entries** typically gained more immediate streams than older songs moving up or down.  
- **USA and Brazil** consistently led in both absolute and per-capita streams.

---

## Chapter 11: Conclusion

The project has successfully analyzed a large, complex dataset using Big Data Analytics principles, demonstrating the power of R programming for data analysis and visualization.

The **insights derived** are not just academic but have real-world applications in **artist management**, **music marketing**, **content recommendations**, and **regional targeting strategies**.

This mini project enabled the authors to gain hands-on experience with:

- Real-world big data handling
- Data cleaning and wrangling
- Statistical data analysis
- Data visualization
- Interpretation and insight extraction

---

## Chapter 12: Future Scope

- **Integration of More Years:** Expand dataset to 2022-2024.  
- **Cross-Platform Analysis:** Compare Spotify data with Apple Music and YouTube.  
- **Machine Learning Models:** Predict chart-topping songs based on trends.  
- **Live Dashboard:** Build real-time updating dashboard using R Shiny.  
- **Incorporate Social Media Metrics:** Analyze the effect of TikTok, Instagram virality.

---

## 📂 Documents and Reports

- **Project Report:**  
  [Click Here to View Full Report](https://github.com/MrHAM17/Spotify_Streaming_Analytics/blob/main/1.%20Project%20All%20IMP%20Docs/BE_COMP_C_28_BDA_Mini_Project_Report.pdf)

---

## 🛠️ Installation Guide

1. **Clone the Repository:** 
   - Using Git
   - Or download the ZIP file and extract it manually.
2. **Install Required R Packages:** 
   - Create a new Colab notebook.
   - Upload the provided code and data files into it.
   - Run the project step-by-step to generate outputs.
3. **(Optional) Run Locally:**
   - Open the project in RStudio.
   - Install the required R packages if needed.
   - Execute the .R scripts sequentially.
     
---

## 📚 References

- Kaggle Spotify Charts Dataset (2019–2021)  
- Wickham, Hadley. *ggplot2: Elegant Graphics for Data Analysis*.  
- Gajewski, J. *Understanding Streaming Services: The Evolution of Music Consumption*.  
- Official R Documentation  

---

**“Let the data tell the story behind the songs. Explore, Analyze, Visualize.”** 🎶📊

---
