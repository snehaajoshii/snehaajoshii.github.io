---
layout: posts
title: "IoMT Secure Dashboard"
date: 2025-04-25 12:00:00 +0000
categories:
  - work
tagline: ""
tags:
  - Cybersecurity
  - Machine Learning
highlight_home: false
body_class: iomt-page
header:
  teaser: /assets/images/IOMT3.jpg
  caption: ""
---
> Python, Streamlit, Scikit-learn, Random Forest, SVM, FastAPI, Matplotlib, Joblib, Pandas

This project is a real-time anomaly detection dashboard built to monitor and detect cyber threats in Internet of Medical Things (IoMT) environments. By leveraging machine learning, it provides a vital layer of security for smart hospital systems.

[Github Repo](https://github.com/BlenWBegashaw/IoMT-Anomaly-Detection2/)

# Inspiration
As healthcare systems become increasingly connected, they also become more vulnerable to cyberattacks. I created this dashboard to provide healthcare IT professionals with a real-time tool to detect and visualize anomalies—such as spoofing, unauthorized access, and ransomware—before they can compromise patient safety or data.

# What it does
The IoMT Anomaly Detection Dashboard offers a suite of tools for real-time monitoring and model evaluation:

- **Real-time Simulation:** Simulates IoMT data streams to provide live predictions on network health.
- **Dual-Model Detection:** Utilizes both **Random Forest** and **Support Vector Machine (SVM)** models to identify anomalies.
- **Model Evaluation:** Displays live confusion matrices to help researchers understand model performance.
- **Automated Logging:** Maintains a `detection_log.csv` of all predictions for post-incident analysis and performance auditing.


## Demo
<div class="video-container">
    <video id="iomt-video" width="800" height="450" controls>
      <source src="/assets/IOMT.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
</div>

<script>
  const video = document.getElementById('iomt-video');
  video.addEventListener('loadedmetadata', () => {
    video.currentTime = 17; // start at 16 seconds
  });
</script>

# How I built it
- **Data Source:** IoMT.csv dataset containing labeled network traffic patterns.
- **Machine Learning:** Developed using Python and Scikit-learn, focusing on Random Forest and SVM classifiers for high-accuracy threat detection.
- **Dashboard:** Built with Streamlit to create an interactive, web-based UI that handles live data processing.
- **Preprocessing:** Utilized StandardScaler and Joblib for efficient model serialization and real-time feature scaling.



### Architecture

 ![Architecture](/assets/images/IOMT2.png)
  

# Challenges I ran into
- **Real-time Performance:** Ensuring the dashboard could process and visualize data points rapidly without lag.
- **Model Accuracy:** Tuning the SVM model to minimize false positives, which are critical in a healthcare setting to avoid "alert fatigue."
- **Data Structuring:** Handling the specific feature requirements of medical IoT devices while maintaining a clean preprocessing pipeline.

# Accomplishments that I am proud of
- Successfully integrated two distinct ML models into a single, cohesive dashboard.
- Developed a functional logging system that records threats automatically.
- Created a tool that bridges the gap between complex machine learning research and practical cybersecurity application.

# What I learned
- How to deploy machine learning models into a live Streamlit environment.
- The specific characteristics of IoMT network traffic and how they differ from standard IT environments.
- Advanced visualization techniques for displaying model evaluation metrics like confusion matrices in real-time.

# What is next for IoMT Dashboard
- Integrate the FastAPI backend to support remote data ingestion from actual medical devices.
- Implement deep learning models to better detect time-series based attack patterns.
- Add an automated alert system that sends notifications via email or SMS when high-severity threats are detected.

---

