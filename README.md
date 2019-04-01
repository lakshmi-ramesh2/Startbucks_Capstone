# Startbucks_Capstone

### Table of Contents

1. [Libraries Used](#libraries)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Acknowledgements](#ack)

## Libraries Used <a name="libraries"></a>

This project was implemented using the Anaconda distribution of Python 3.0. The most important python libraries that were used are:

1. NumPy and Pandas - for data cleansing and wrangling
2. Seaborn and Matplotlib - for visualization
3. Sklearn - for clustering 

## Project Motivations<a name="motivation"></a>

This project utilizes simulated data about Starbucks customer behavior using their mobile application. Primarily, the data set contains 3 data sets:

Portfolio: This data set contains information about various offers, the offer type, validity etc.
Profile: This data set contains information about Starbucks customers along with some demographic information
Transcript: This data set contains transactions such as purchases as well as offer interaction details

From this data set, we will be primarily trying to explore how Starbucks customers interact with offers they receive and look for similarity between customer segments to inform what types of offers might work best for the various segments.

The primary areas of interest for this project are:

### 1. CHANNEL ANALYSIS
Exploring channels and which channels work best is a common marketing problem. We will attempt to answer which channels do most completed offers come from. Understanding the best performing channels can result in spend optimization and ensure that the larger chunk of the marketing budget goes to the best channels.

### 2. OFFER TYPE ANALYSIS
In this section, we will attempt to answer how offer received, viewed and completion numbers change with offer types. Understanding how offer interactions differ based on offer types can suggest which types of offers to invest in more.

### 3. DEMOGRAPHIC ANALYSIS
We will attempt to answer how age, gender and income differs between different user groups. The 4 main user groups we are interested in are:

Users that receive offers, view offers and complete offers
Users that receive offers, view offers and DO NOT complete offers
Users that receive offers, DO NOT view offers and DO NOT complete offers
Users that receive offers, DO NOT view offers and complete offers
Based on the above, we may be able to understand better the demographics of the converting users and also inform improvements to offers for different user groups.

### 4. CLUSTER ANALYSIS
We will attempt to identify similarity between users and cluster them into segments to derive insights. We will attempt to answer questions like, which customer segments make the most number of purchases, which customer segments have the most offer completion rate for bogo offers etc.

This analysis will help understand the current customer base and how they respond to offers, but can also help with assigning new customers into existing segments to dictate what offers would work best for them.

More details can be found in this blog post: https://medium.com/@lakshmiaraman/customer-behavior-analysis-and-segmentation-for-starbucks-977f1d2291f7

## File Descriptions <a name="files"></a>

There are 2 files provided:

1. Starbucks_Capstone_notebook.ipynb - Jupyter notebook containing all the code and descriptions
2. Starbucks_Capstone_notebook.html - HTML version of the notebook 

## Acknowledgements <a name="ack"></a>

The data set for this project was provided by Udacity.

