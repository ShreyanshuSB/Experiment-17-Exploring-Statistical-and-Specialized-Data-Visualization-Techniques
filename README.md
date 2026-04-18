## **Experiment 17**

**Name:** Shreyanshu Swastik Behera  
**PRN:** 25070123149  
**Batch:** ENTC A1   

### **Title**
Implementation of Statistical and Specialized Data Visualization Techniques

### **Aim**
To study and implement advanced statistical visualization methods in Python, focusing on data distributions, correlation analysis, and categorical relationships using the **Matplotlib** and **Seaborn** frameworks.

### **Objectives**
* To evaluate the significance of statistical plotting in data-driven decision-making.
* To utilize **Box Plots** for quartile analysis and outlier detection.
* To model relationships between variables using **Scatter Plots** integrated with **Regression Lines**.
* To analyze the density and spread of numerical data via **Histograms**.
* To represent proportional categorical data using **Pie Charts**.
* To apply advanced plot customization for professional-grade presentation.

---

### **Theory on Specialized Visualization**
Specialized statistical visualization goes beyond simply plotting raw numbers; it aims to reveal the mathematical "soul" of the data, including its central tendency, dispersion, and variance.

#### **1. Box Plots (Whisker Plots)**
A Box Plot summarizes a dataset through five key statistics: the minimum, first quartile ($Q_1$), median, third quartile ($Q_3$), and maximum. It is an essential tool for an engineer to identify **outliers**—data points that deviate significantly from the norm and could indicate sensor errors or experimental anomalies.

#### **2. Scatter Plots and Regression**
Scatter plots show the raw interaction between two numerical variables. By adding a **Regression Line**, we can mathematically visualize the trend (positive, negative, or constant), helping us predict how one variable (like "Engine Power") influences another (like "Fuel Efficiency").

#### **3. Histograms and Data Density**
Histograms provide a visual representation of the frequency distribution of a continuous variable. By dividing data into "bins," we can observe whether the data follows a specific curve, such as a Gaussian (normal) distribution, which is critical in quality control and signal analysis.

---

### **Data Visualization Operations**

* **Demographic & Proportional Analysis:** We used categorical plotting to break down student-related data. **Pie Charts** were implemented to visualize the ratio of grades (A, B, C) and gender distribution, utilizing the `autopct` parameter to automatically calculate and display percentages on the chart slices.
* **Frequency Mapping:** Using both the **Cars93** dataset and custom student records, we generated Histograms for "Price" and "CGPA." This allowed us to observe the skewness of the data—identifying, for example, if most students fall into a specific CGPA bracket.
* **Outlier Identification:** We generated **Box Plots** for numerical features. By analyzing the "whiskers" and the points beyond them, we successfully identified outliers, which is a vital step in data cleaning before feeding information into a machine learning model.
* **Professional Customization:** To ensure the plots were readable and report-ready, we utilized `plt.figure(figsize=(...))` to control dimensions and added descriptive labels using `plt.title()`, `plt.xlabel()`, and `plt.ylabel()`.

---

### **Applications in Engineering**
* **Quality Assurance:** Using Histograms to monitor the variance in the dimensions of manufactured electronic components.
* **Predictive Maintenance:** Leveraging Scatter plots with regression to predict when hardware might fail based on temperature and usage hours.
* **Resource Allocation:** Representing department-wise budget or power consumption using proportional Pie charts.
* **Signal Integrity:** Using Box plots to detect noise spikes or outliers in communication signals.

### **Conclusion**
This experiment highlights that specialized visualization is a cornerstone of deep data exploration. While basic charts give a surface-level view, tools like Box plots, Histograms, and Regression lines reveal hidden statistical properties such as density and correlation. For an ENTC student, mastering these techniques in Matplotlib and Seaborn is crucial for interpreting experimental results and building accurate predictive models.

---
