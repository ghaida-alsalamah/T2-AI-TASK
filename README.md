# T2-AI-TASK

Data Visualization & AI System
Group Project – T2
1. Project Introduction
This project simulates a real-world data science and artificial intelligence workflow. It covers the full lifecycle of a data-driven system, starting from data collection and preprocessing, moving through visualization and feature engineering, and ending with an interactive AI model presented through a professional website.

The project emphasizes not only technical implementation but also teamwork, analytical thinking, and professional communication, reflecting industry-level data science and AI practices.

2. Dataset Description
The dataset used in this project is a large-scale real-world dataset containing more than 20,000 rows, strictly satisfying the mandatory data requirement.

Why this dataset was chosen:

It represents a real-world scenario relevant to the project goal (YouTube Trend Analysis).

It is large enough to support reliable visualization and robust machine learning models.

It contains multiple features suitable for complex feature engineering and modeling.

It enables meaningful analytical insights and trend discovery across various categories.

What the data represents:

The dataset reflects real-world digital behaviors and engagement patterns on YouTube, allowing for deep analysis, visualization, and prediction through machine learning models.

3. GitHub Repository Structure
This repository serves as a shared collaborative workspace for the entire team:

Repository Link: https://github.com/cyberevil545/youtube-videos-data-for-ml-and-trend-analysis

Contents:

Dataset files (20,000+ records).

Source code for data preprocessing and cleaning.

Source code for feature engineering.

Source code for interactive Plotly visualizations.

Source code for AI/Machine Learning models.

Source code for the Streamlit website.

4. Website Overview
The project includes an interactive website that presents the system in a clear and professional way.

Technology Stack:

Python: Primary programming language.

Plotly: For mandatory interactive visualizations.

Scikit-learn: For building and evaluating the AI model.

Streamlit: Web framework for the interactive UI.

Deployment: The website is deployed online and is accessible via a live link for real-time interaction.

5. Website Pages
Page 1: Information Page (Project & Data Explanation)

This page introduces the context of the project:

The Data: An overview of YouTube metadata (Duration, Bitrate, Views, Likes).

The Choice: Why this 20,000+ row dataset was selected to ensure statistical reliability.

The Problem: Helping content creators understand the technical drivers of video success.

The Goal: Extracting insights to optimize video quality and engagement.

Page 2: Visualization & Feature Engineering

Data Requirement

The dataset contains at least 20,000 rows, ensuring meaningful machine learning outcomes and reducing overfitting.

Visualization

All visualizations are fully interactive using Plotly, including:

Interactive scatter plots showing correlations.

Heatmaps of feature relationships.

Multi-view dashboards for trend exploration.

Feature Engineering

We applied several techniques to improve model performance:

Engagement Rate: Calculating (Likes/Views) to measure content quality.

Encoding: Converting categorical data (Categories) into numerical formats.

Scaling: Normalizing numerical features for better model stability.

Analytical Discussion

Observed Patterns: High-definition videos (1080p and above) show a 20% higher engagement rate on average.

Trends & Correlations: A strong positive correlation was found between comment counts and the likelihood of a video trending.

Visualization Insights: Interactive charts revealed that specific categories like "Music" are less dependent on bitrate than "Gaming."

Engineering Impact: Adding the "Engagement Rate" feature improved our model's predictive power significantly.

Limitations: The data does not include thumbnail images, which are a major external factor in video clicks.

Page 3: AI Model Page

Model Type

We implemented a Random Forest Regression model to predict video views.

Interactivity

Users can manually enter values (Duration, Category, Quality) and receive real-time predictions from the trained AI model.

Evaluation Metrics

The model is highly reliable and has been evaluated using:

R² Score: 84% (0.84)

Mean Absolute Error (MAE): To measure prediction variance.

6. Project Objectives & Learning Outcomes
Through this project, the team has achieved:

Simulation of a real-world AI lifecycle.

Strengthened collaboration via GitHub.

Mastery of interactive data visualization using Plotly.

Application of professional feature engineering and model evaluation.

7. Team Members
Ghaida Alsalamah

Layan Al-Sulaiman

Sara Al-Hamdan

Lama Faden

8. Conclusion
This project integrates data engineering, visualization, machine learning, and web development into a single cohesive system. It reflects real-world practices and prepares us for professional industry-level AI projects. By utilizing a dataset of over 20,000 rows and achieving an 84% model score, we have successfully built a robust system for YouTube trend analysis.
