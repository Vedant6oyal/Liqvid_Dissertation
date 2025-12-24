# 🎓 Predictive Analysis of Student Dropout in An E-Learning Platforms

> **MSc Business Analytics Dissertation | UCL School of Management**  
> *Transforming 50M server logs into actionable retention insights*

[![Video Presentation](https://img.shields.io/badge/📹_Watch-Video_Presentation-red?style=for-the-badge&logo=youtube)](https://youtu.be/hlM3BopJWPc)

---

## 🚀 Project Overview

Over **80% of learners drop out** of MOOCs and online courses, damaging platform credibility and reducing customer lifetime value. This project tackles that challenge head-on.

Working with **Liqvid**, an AI-driven English learning company, I analyzed **50 million server logs** spanning July 2021 to April 2024 to build a predictive system that identifies at-risk learners early—enabling timely interventions that improve retention and ROI.

**Key Achievement:** Built a model that flags **86.7% of actual dropouts** with **72.8% precision**, successfully targeting over 86% of Liqvid's 57.5% dropout rate.

---

## 🎯 Why This Matters

**High Dropout = Lost Learning + Lost Revenue**

- Early prediction enables timely intervention
- Improved retention drives platform credibility
- Data-driven insights support strategic decisions, not just reporting
- Actionable system ready for real-time deployment

---

## 🔍 Key Findings

### 1. **Recency is the Silent Signal**
- **Days Since Last Event** is the #1 predictor of dropout (correlation: +0.434)
- Dropouts average **14.7 days** of inactivity vs. **6.5 days** for active learners
- Learners inactive for 14+ days face significantly higher dropout risk

### 2. **Diverse Content Exploration Drives Retention**
- High-diversity learners are **19x more active** (756.7 vs 39.5 total events)
- Content variety (topic & chapter entropy) correlates with lower dropout rates
- Breadth of engagement matters as much as depth

### 3. **The Mid-Tenure Paradox**
Consistent learners (90–180 days tenure) showed **higher dropout rates** than expected—indicating learner fatigue, not just disengagement. *Timing matters for interventions.*

### 4. **Sessions Trump Completion**
- Non-dropouts have **116.7% more sessions** on average
- It's the **routine and habit** that separates stayers from leavers
- Total time-on-task: +63% higher for non-dropouts

---

## 📊 Model Performance

| Metric | Score | Business Impact |
|--------|-------|-----------------|
| **Recall** | 86.7% | Captures nearly 9 out of 10 actual dropouts |
| **Precision** | 72.8% | 3 out of 4 flagged learners are genuinely at risk |
| **F1 Score** | 0.791 | Strong balance between sensitivity and reliability |
| **PR AUC** | 0.8409 | Outperforms Logistic Regression, Random Forest, XGBoost, and MLP |

**Temporal Validation:** Model performance remained consistent over 8 months, adapting reliably to evolving student behaviors.

---

## 👥 Learner Segmentation

Three distinct behavioral segments emerged, each requiring tailored interventions:

### 🔴 At-Risk Learners (34.7%)
- **Dropout Rate:** 64%
- **Profile:** Low activity, very few sessions (~0.7 avg)
- **Strategy:** "Easy way back in" — quick wins, streak revival, friendly reminders

### 🟡 Mid-Tier Engaged (46.3%)
- **Dropout Rate:** 49.5%
- **Profile:** Moderate usage, steady but not intensive
- **Strategy:** "Stay on track" — weekly goals, momentum nudges

### 🟢 Power Users (19.0%)
- **Dropout Rate:** 50.7%
- **Profile:** High interaction volume, consistent sessions
- **Strategy:** "Level up & lead" — badges, advanced content, mentoring roles

---

## 💡 Actionable Recommendations

### Immediate Actions

1. **Implement Recency-Based Alerts**  
   Flag learners with 7+ days of inactivity for automated reminders

2. **Target Mid-Stage Learners**  
   Focus interventions at 60–120 days since signup (peak engagement + fatigue onset)

3. **Promote Content Diversity**  
   Encourage exploration of new topics and chapters to boost stickiness

4. **Monitor Session Frequency**  
   Low session counts are 2–3x more likely to indicate dropout (correlation: −0.347)

5. **Personalize by Segment**  
   Use behavioral clusters to tailor messaging and support

### Implementation Roadmap

| Action | Owner | Timeline |
|--------|-------|----------|
| Design inactivity alert system | Product Team | Week 1–2 |
| Roll out mid-stage user nudges | CRM/Retention | Week 2–4 |
| A/B test content diversity rewards | Product/Growth | Week 2–5 |
| Build segment dashboard | Data Science | Week 3–6 |

---

## 🛠️ Technical Stack & Skills Applied

### Machine Learning & Analytics
- Predictive modeling (Logistic Regression, Random Forest, XGBoost, MLP)
- Feature engineering from behavioral data
- Temporal validation and model calibration

### Data Engineering
- Processed 50M+ server logs (3+ years of data)
- 30-day behavioral snapshot windows
- Handled imbalanced datasets

### Visualization & Storytelling
- Dashboard design for non-technical stakeholders
- Clear communication of complex insights
- Business-focused metrics and KPIs

### Project Management
- Gantt charts and Trello for workflow tracking
- Cross-functional stakeholder communication
- User-centric design principles

---

## 🎁 Bonus: InsightBot Agent

Built a conversational AI using **LangChain** that lets staff query learner data in plain English.

**Example queries:**
- "Which batch has the highest dropout rate this month?"
- "Show me engagement trends for at-risk learners"

Integrated into the dashboard prototype for technical and product teams.

---

## 🔮 Future Exploration

### What I'd Explore Next

1. **Sequence/Survival Analysis**  
   Predict precise "time to churn" for more targeted interventions

2. **Psychological & Contextual Data**  
   Integrate motivation, internet access, and socio-economic factors (ethically)

3. **Advanced Personalization**  
   Develop granular learner personas beyond the three core segments

4. **Real-Time Automation**  
   Create triggered workflows based on live risk scores

---

## 📚 Key Learnings

### 1. **Complexity ≠ Value**
Fancy algorithms aren't always superior to simple, actionable insights that stakeholders can trust and use. *Clarity trumps convolution.*

### 2. **Communication Shapes Impact**
Building a great model isn't enough—effectively explaining it in plain language drives real change and adoption.

### 3. **Iteration Beats Perfection**
Progress came from many small, imperfect improvements, not one big breakthrough. A lesson applicable far beyond data science.

### 4. **Real-World Data Is Messy**
Navigating imperfect data taught resilience, patience, and structured problem-solving. *Embrace the mess as a learning opportunity.*

### 5. **Trust Beats Complexity**
Calibrated, explainable scores build user confidence and drive adoption more effectively than black-box models.

---

## 🎬 Video Presentation

Watch the full dissertation presentation:

[![YouTube Video](https://img.youtube.com/vi/hlM3BopJWPc/maxresdefault.jpg)](https://youtu.be/hlM3BopJWPc)

---

## 📧 Contact

**MSc Business Analytics | UCL School of Management**  
Candidate ID: MKDS6

For questions, collaboration opportunities, or further discussion about this project, feel free to reach out.

---

## 📄 License

This project was completed as part of the MSc Business Analytics program at UCL School of Management.

---

*"From raw logs to risk insights—empowering proactive intervention in e-learning."*
