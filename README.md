# SIH-2022
Smart India Hackathon 2022



# ProfessionPro - Smart India Hackathon 2022 Runner-up

## Overview

**Project Name:** ProfessionPro  
**Event:** Smart India Hackathon (SIH) 2022  
**Problem Statement Code:** DR710  
**Theme:** Smart Education  
**Team Name:** ProSol  
**Team Members:** 
1. Harsh Loomba (Team Leader)
2. Arkadeep Acharya
3. Ashutosh Kumar Singh
4. Asmit Ganguly
5. Harshit Dhankhar
6. Seema Meena  
**Mentor:** Mayank Agarwal (ML Domain Expertise)  
**Institute:** Indian Institute of Technology Patna  
**Result:** Runner-up among 30,000+ participating teams  
**Location:** Vishakapatnam  

## Problem Statement

In the rapidly changing job market, it can be challenging for job seekers to find career paths aligned with their skills and market demands. The aim of the project was to develop an **AI-powered web portal** that processes an individual's resume to suggest potential career paths. We achieved this using Natural Language Processing (NLP) techniques for resume parsing and machine learning models to predict the most suitable career options based on job trends and personal skills.

**Objective:**
To help job seekers (especially the unemployed youth in their early 20s) identify relevant job domains and ease the job search process by integrating career suggestions with the **National Job Database**.

## Approach

![image](https://github.com/user-attachments/assets/ecc1fbd1-a987-4d57-a81f-18e1b24fb94f)


### 1. **NLP-based Resume Parsing**
We utilized basic **Nuance-based Splitting** along with the **Natural Language Toolkit (NLTK)** library to extract key details from the resumes provided by users. This process helped identify critical information, such as:

- Educational background
- Skills and certifications
- Work experience

Using text-cleaning techniques such as stopword removal, tokenization, and word frequency analysis, we extracted meaningful insights from the resumes. The extracted data was further processed to suggest career paths.

### 2. **Career Domain Classification**
The resumes were categorized into different job domains, such as Data Science, Java Development, Web Design, HR, and others. We trained machine learning models like **K-Nearest Neighbors (KNN)** and **Naive Bayes** to classify resumes into these predefined categories based on the skills and experience mentioned.

### 3. **Career Dendrogram**
By analyzing **past employment trends** and **market demand** (sourced from national job databases), we developed a **Career Dendrogram**, which acted as a decision tree to guide users toward the most suitable career paths.

- The **ML framework** was built using **Python** and integrated with the job database.
- A backend developed using **Django** handled the processing, while the **MySQL** database stored user profiles, resumes, and job opportunities.

### 4. **MCQ-based Quiz for Career Guidance**
For individuals without a resume or those unsure about their career goals, we designed a **skills and interests quiz**. The quiz results were processed using machine learning models to suggest the best career paths based on individual preferences.

### 5. **User-Friendly Web Interface**
The **ProfessionPro Web Portal** had an interactive UI built using **HTML5, CSS3**, and **JavaScript**, allowing users to easily upload their resumes or complete the career quiz. The portal displayed career suggestions based on the user's data and national job trends.

### 6. **Future Integration with National Job Database**
In the future, our goal is to integrate **real-time job opportunities** from the **National Job Database** into ProfessionPro. This will enable users to directly search for and apply to jobs relevant to their skills and career suggestions, streamlining the job-seeking process for unemployed individuals across India.

## Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Django (Python-based)
- **Database:** MySQL
- **NLP:** NLTK (for resume parsing and text cleaning)
- **Machine Learning Models:** 
  - K-Nearest Neighbors (KNN)
  - Naive Bayes
  - One-vs-Rest Classifier
- **Visualization:** Seaborn, Matplotlib (for data visualization and career trends analysis)

## Key Features

- **Automated Resume Parsing:** Uses NLP to analyze resumes and extract relevant career details.
- **Career Suggestions:** Based on skillsets, experience, and market demand, the portal provides users with the most promising career paths.
- **Quiz for Career Guidance:** An interactive quiz helps users with no prior experience discover potential job domains.
- **User-Centered Design:** Easy-to-use interface for both resume upload and quiz completion.
- **Real-Time Job Market Trends:** The platform is designed to integrate job market trends from national databases to provide up-to-date career suggestions.

## Achievements

- Runner-up among 30k+ participating teams at Smart India Hackathon 2022.
- Successfully demonstrated how AI can be used to bridge the gap between job seekers and employers by providing personalized career guidance.
- Recognized for the potential to significantly ease the job search process for unemployed individuals in India, especially in their early 20s.

## Future Directions

1. **Full Integration with the National Job Database:** By leveraging government and private-sector job databases, we aim to provide real-time job suggestions and opportunities tailored to each user.
2. **Advanced NLP and AI Models:** Improving resume parsing accuracy by integrating more sophisticated NLP techniques and deep learning models.
3. **Mobile App Version:** Developing a mobile-friendly version of ProfessionPro to make career guidance more accessible.
4. **Real-time Job Matching:** Automatically suggesting job opportunities to users as soon as they upload their resumes, based on current market trends.

---

ProfessionPro offers a streamlined, AI-powered career guidance system that can significantly aid unemployed individuals in finding their ideal job paths, reducing the gap between skillsets and job opportunities.
