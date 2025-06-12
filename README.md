# PHASE-2-DATA-PROJECT
Final Project for Phase 2

# 🎥 Film Industry Analysis for Business Expansion

This project analyzes various film industry datasets to uncover trends that can guide a company's strategic entry into the entertainment industry. The company aims to establish a successful movie studio. However, due to limited experience in film production, the business needs insight-driven guidance. This analysis will highlight the most profitable, well-received, and promising areas in film today.

By integrating multiple datasets I aim to explore current industry patterns to provide actionable recommendations on the types of films the new studio should prioritize.


## 💼 Business Understanding

With streaming platforms, global cinema, and digital distribution evolving, film production has become both an art and a high-stakes business. Identifying what makes a movie successful requires analyzing box office numbers, critic reviews, audience preferences, and market performance.

This analysis will help answer the following key business questions:

- **Which genres receive the best critical reception?**
- **What genres offer the highest return on investment (ROI)?**
- **Are there specific directors whose films consistently perform well internationally?**
- **What languages are associated with popular films?**

These insights will equip the new studio team with reliable data to commission projects that align with the market demand and maximize profitability.

## 📊 Datasets

This project draws on a robust combination of industry datasets:

- **Box Office Mojo**: Gross earnings and box office performance.
- **Rotten Tomatoes**: Critic and audience scores, along with review sentiment.
- **IMDb Links**: Unique identifiers to cross-reference movies across datasets.
- **TheMovieDB**: Metadata on movies including genres, languages, production countries, popularity, and more.
- **The Numbers**: Financial details such as production budgets and revenues to help calculate ROI.

Together, these datasets offer a comprehensive view of the global film landscape.

### *1️⃣ Data Exploration*  
- This phase focuses on understanding the dataset, identifying important columns, and investigating potential relationships that could be explored.  
- Assessing the structure of the data, will determine which columns are crucial for this analysis, and evaluate whether the data is clean or requires attention
I will investigate the different subsets of the data to understand the distribution, data types, and to identify any obvious issues (e.g., missing values, inconsistencies).  
- The goal is to identify any initial patterns, issues, or opportunities for further exploration and to form hypotheses that guide the next steps in the analysis.

### *2️⃣ Data Preparation & Cleaning*  
- After initial exploration, focus will now be on preparing the data for further analysis by accurately merging various datasets, ensuring that relationships are explored correctly.  
- Handle any missing values through imputations, deal with outliers, and perform other cleaning tasks (e.g., removing duplicates, handling inconsistencies).  
- The data is structured in a way that allows to explore relationships in greater depth and ensures that the datasets are accurate, consistent, and ready for analysis.  
- This stage ensures that the data is in a clean, usable state for modeling and deeper insights.

  ### *3️⃣ Data Analysis*  
This stage is divided into the following:

#### 📊 Data Visualization  
- Exploring visual trends related to genres, ratings, ROI, and other variables.  
- Visualization types include bar plots, box plots, histograms, and scatter plots to surface patterns.  

#### 🧪 Hypothesis Testing  
- It is designed to statistically support or challenge the patterns observed in visual analysis.  
- I will conduct a series of tests on the different assumptions using methods like t-tests and ANOVA.  
- Focusing on validating insights about genre success, director performance, and audience preferences.  

### *4️⃣ Business Recommendations*  
- Synthesizing results into clear, actionable insights for the new movie studio.  
- Align the recommendations with business goals.  
- Focus on helping decision-makers prioritize **genres**, **directors**, **languages**, and **film types** based on profitability, audience reception, and global appeal.

### *5️⃣ Limitations of The Analysis*  
- I shall discuss the limitations of the analysis, such as potential biases in the dataset, missing information, and sampling constraints.  
- Acknowledging areas where further exploration, data collection, or improved methods could enhance the results.

  ## 📊 Key Visualizations 
Below are the critical visualizations that helped provide my insights into the film industry:

#### 1️⃣ Understanding the Relationship between Genres and Ratings

![Top Genres by Average Rating (Audience vs Critic)](images/v1.png)

#### 2️⃣ Understanding the Relationship between Genre and ROI

![Normalized ROI per Genre](images/v2.png)

#### 3️⃣ Understanding the Relationship between Language and Popularity

![Popularity Distribution by Top 20 Languages](images/v3.png)

#### 4️⃣ Understanding the Relationship between Directors and Worldwide Gross Earnings

![Top 10 Directors by Worldwide Gross](images/v4.png)

## 📌 Conclusion
This analysis shows that G-rated and family-friendly films offer the highest ROI, while genres like Drama and Animation consistently receive strong ratings, and a few key directors drive higher foreign revenue. English remains the dominant language for popular films, but non-English content also shows potential. These insights can help guide data-driven decisions on genre focus, content rating, and director partnerships for a successful market entry.

## 💻 Technologies Used
- **Python** - `Pandas`, `Matplotlib`, `Seaborn`, `NumPy`
- **Jupyter Notebook**

## 📂 Repository Structure
- `ZippedData/` → Folder containing the cleaned datasets used in analysis
- `scripts/` → Folder containing Script to automatically unzip ZippedData into Data Folder locally 
- `Data/` → Folder with unzipped data 
- `images/` → Folder containing images used throughout the notebook
- `README.md` → This project overview file
- `index.ipynb` → Jupyter Notebook containing full analysis
- `presentation.pdf` → Power Point presentation for investor/stakeholder insights
