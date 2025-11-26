# Data Visualization Project Report  
## A Multidataset Analysis of VR User Comfort, Risk Factors, and Behavioral Patterns

---

## Abstract

This project analyzes virtual reality usage by synthesizing multiple datasets related to demographics, hardware adoption, immersion levels, motion sickness, emotional responses, and consumer behavior. By integrating diverse VR and AR data sources, the project identifies which factors most strongly influence user comfort, discomfort, and overall VR experience quality. Through both descriptive visualizations and predictive modeling, the study highlights the relationships between age, gender, device type, familiarity with VR, and emotional response patterns. The visual prototypes provide an interactive and comparative understanding of how different groups engage with VR, setting the foundation for improved user-centered design and risk mitigation strategies across VR platforms.

---

## Project Overview

This project examines how different groups of people experience virtual reality depending on their demographics, hardware choices, and behavioral tendencies.  
Instead of relying on a single dataset, the analysis synthesizes insights from multiple Kaggle sources covering VR usage, headset adoption, emotional response, consumer behaviors, immersion scores, and accessibility conditions.

The central goal is to understand **what factors predict comfort, discomfort, and overall immersion** in VR systems.  
The project uses both descriptive visualizations and predictive modeling to uncover meaningful patterns that shape VR user experience.

---

## Data

The data I propose to visualize for my project is ... found ih the following locations: 
 - https://www.kaggle.com/datasets/lumaatabbaa/vr-eyes-emotions-dataset-vreed
 - https://www.kaggle.com/datasets/yapwh1208/availability-of-education-for-assistive-technology
 - https://www.kaggle.com/datasets/yapwh1208/availability-of-education-for-assistive-technology
 - https://www.kaggle.com/datasets/leetheoiv/steam-virtual-reality-vr-video-games-dataset
 - https://www.kaggle.com/datasets/szhao2020/vr-gaming-network-traffic
 - https://www.kaggle.com/datasets/programmer3/emotion-recognition-in-mobile-vr-films
 - https://www.kaggle.com/datasets/ilokabenneth/augmented-reality-consumer-behaviour-consumer-enga

## Questions & Tasks

## Key Questions & Findings  
*(Descriptive + Predictive)*

### 1. How do VR headsets differ across demographics, comfort levels, and immersion scores?  
**Finding:**  
PlayStation VR has the largest user base. HTC users tend to have longer sessions and lower motion sickness. Oculus users fall between the two.

---

### 2. What demographic factors predict comfort or discomfort in VR?  
**Finding:**  
- Younger male users tend to experience more sickness  
- Female users show lower sickness and stay longer in VR  
- Other-gender populations show the greatest variability due to sample size  

Demographics clearly influence comfort outcomes.

---

### 3. What behavioral factors contribute to immersion or discomfort?  
**Finding:**  
- Long sessions increase immersion and discomfort simultaneously  
- Frequent users adapt faster and show lower sickness  
- Multi-device users report the highest comfort and engagement  

Predictive modeling will quantify which factors matter most.

---

### 4. Are there geographic differences in VR or assistive technology adoption?  
**Finding:**  
Countries with higher educational and technological funding show greater adoption. Under-resourced regions lag significantly.

---

### 5. What combinations of factors best predict a positive or negative VR experience?  
**Approach:**  
Using regression or classification models with:  
- Age  
- Gender  
- Headset  
- Session duration  
- Experience level  

Outputs include comfort score, immersion rating, and risk probability.


 * (insert your question or task here) What is the most ocmmon mainstream headset X vary over time?
 * (insert your question or task here) Is there any correlation between Gender?
 * (insert your question or task here) Are there interesting spatial patterns in the data?
 * (insert your question or task here) How many X are there across different Y?
 * (insert your question or task here) Where does the US rank in Assistive Technolgoy?
 * (insert your question or task here) How many schools have adopted VR Usage?
 * (insert your question or task here) What are the risk factors of VR Usage?
 * (insert your question or task here)  Is there any correlation between Model Type?



---
## Sketches

### Risk Factor Tree  
Hierarchy showing: All users → Device → Gender → Comfort Risk.

### Comfort Severity Heatmap  
A grid showing discomfort intensity across headsets, demographics, and behaviors.

### Predictive Model Flow Diagram  
Visualizing relationships between user traits and VR outcomes.

---

## Project Goals

- Identify what makes VR comfortable or uncomfortable  
- Compare major headset demographics and behavioral patterns  
- Understand consumer behavior and its relationship to VR outcomes  
- Develop predictive models for comfort, immersion, and user engagement  
- Produce clear, interpretable visualization prototypes  

---

## Why This Project Matters

VR is rapidly entering entertainment, education, therapy, and accessibility.  
Understanding user comfort and risk factors is critical for:

- broader adoption  
- safer user experiences  
- better hardware design  
- enhanced accessibility  
- informed decision-making by developers and researchers  

These results can influence future VR safety guidelines and consumer experience design.

---


## Prototypes

I’ve created a proof of concept visualization of this data. The visiualiatios range from stater plot, to data trees. 


[![image](https://github.com/fokalview/VR-Data/blob/master/3panel.png)](https://vizhub.com/fokalview/f2e723cc55194e98ab325c524371c4e4)

<div align="center">

### **PlayStation VR**  
### **A 3 Panel Spread of PlayStation VR, HTC, and Oculus**

</div>

---

[![image](https://github.com/fokalview/VR-Data/blob/master/PlaystationVR.png)](https://vizhub.com/fokalview/0cc21ddd8b9c403b856b1dbe925a4ab5)

<div align="center">

### **PlayStation VR**

</div>

---

[![image](https://github.com/fokalview/VR-Data/blob/master/HTC.png)](https://vizhub.com/fokalview/16bb6b65f8894e7383ba5840939508d5)

<div align="center">

### **HTC**

</div>

---

[![image](https://github.com/fokalview/VR-Data/blob/master/oculus.png)](https://vizhub.com/fokalview/02c750bd8dea4c309fd682feb4ce7470)

<div align="center">

### **Oculus**

</div>

---

[![image](https://github.com/fokalview/VR-Data/blob/master/Assitivetech.png)](https://vizhub.com/fokalview/5325ee30f3aa4482bba707138034e637)

<div align="center">

### **Assistive Technology**

</div>

---

[![image](https://github.com/fokalview/VR-Data/blob/master/VRExp.png)](https://vizhub.com/fokalview/0b4d4f422e2f4721b963b242b6388e84)

<div align="center">

### **VR Experience**

</div>

---

[![image](https://github.com/fokalview/VR-Data/blob/master/Immerion%20SCore.png)](https://vizhub.com/fokalview/772e7b2285d643cbaab3892a6d7d9300)

<div align="center">

### **Impact on Score**

</div>

---

[![image](https://github.com/fokalview/VR-Data/blob/master/Engagment.png)](https://vizhub.com/fokalview/634ce52577aa4d509d022628e38526c3)

<div align="center">

### **Engagement**

</div>

---
[Source – 3 Panel Spread](https://vizhub.com/fokalview/f2e723cc55194e98ab325c524371c4e4)

[Source – PlayStation VR](https://vizhub.com/fokalview/0cc21ddd8b9c403b856b1dbe925a4ab5)

[Source – HTC Vive](https://vizhub.com/fokalview/16bb6b65f8894e7383ba5840939508d5)

[Source – Oculus](https://vizhub.com/fokalview/02c750bd8dea4c309fd682feb4ce7470)

[Source – Assistive Tech](https://vizhub.com/fokalview/5325ee30f3aa4482bba707138034e637)

[Source – VR Experience](https://vizhub.com/fokalview/0b4d4f422e2f4721b963b242b6388e84)

[Source – Impact on Score](https://vizhub.com/fokalview/772e7b2285d643cbaab3892a6d7d9300)

[Source – Engagement](https://vizhub.com/fokalview/634ce52577aa4d509d022628e38526c3)


## Open Questions

I am not sure that I am going ot do this correctly but i am going to do my best to try. Here are a few views that i am not sure about: 

https://vizhub.com/fokalview/5e0d145e049d46a9ac27ba580bd3d589
https://vizhub.com/fokalview/c849b29a34cd452abb20fe62bfea0d9d
https://vizhub.com/fokalview/2f7d8ea52aa549028a94af36c2b17d41
https://vizhub.com/fokalview/3c0b21fb8d3e435a9f4dcaadc9b2bf2e



## Milestones

I have made a scatter plot
I was able to finlally import the docutmetns!
I was able to start iterateing the scater pl;ot and data into something abiut more unique and suited toward the data that i have. 

## Conclusion

This multidataset VR analysis highlights strong relationships between user demographics, headset design, behavioral tendencies, and the comfort or discomfort people feel in virtual environments. Patterns across age, gender, and experience reveal that VR outcomes are far from uniform. Device choice plays a significant role, and behavioral factors such as session duration and familiarity amplify or reduce discomfort risk.

By structuring the project around both descriptive comparisons and predictive modeling, the work lays a foundation for future studies in VR ergonomics, comfort optimization, and personalized VR experiences. The visual prototypes make these findings accessible and interpretable, translating complex VR datasets into clear insights about how people truly interact with virtual environments.

This analysis provides a starting point for deeper exploration into predictive modeling, cross-device comfort optimization, and understanding the behavioral elements that shape healthy, enjoyable VR engagement.


