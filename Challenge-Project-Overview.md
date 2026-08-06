---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

---

## 📋 BTT Internal Evaluation Notes
*(This section is for BTT staff only — remove before sharing with students)*

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | GREEN | The tech stack is centered around Python and its popular libraries for machine learning and data analysis. |
| Data Readiness | YELLOW | Publicly available data suggests some readiness, but datasets from diverse sources may require significant cleaning and integration efforts, potentially occupying a majority of the work period. |
| Resource Check | GREEN | Utilizes accessible hardware (Google Colab free tier) with no specialized equipment needed. |

**Student Fit Score:** 7/10  
**Technical Depth Score:** 6/10  
**Overall Recommendation:** REVISE

**Advisor Feedback Draft:**
Strength: The project allows students to engage with various ML techniques, broadening their skill set. Actionable Adjustments: 1. Narrow the scope to ensure manageable deliverables within the semester timeline; focus on key features that align closely with the project goals. 2. Define a comprehensive data cleaning strategy and evaluation framework to address ethical considerations in AI deployment. Call to Action: Encourage a revised project plan with streamlined goals for improved execution.

---

# Founder Intelligence Platform - Combined 2025 (CFRM)

**Company / Org:** G&M  
**Challenge Advisor:** Sam Ogah, samuel.ogah@zicloudtech.com  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About G&M

G&M is focused on leveraging data and technological innovations to support under-capitalized founders in the entrepreneurial ecosystem. We operate at the intersection of AI technology and social impact, aiming to unlock capital for diverse talent.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use data sets from USPTO, Tech Hubs, and ecosystem datasets (LinkedIn, YouTube, Instagram), as well as behavioral frameworks on coachability, entrepreneurial mindset, and grit established in the two separate 2025 SRI and CFRM projects. The project will involve data cleansing and ML techniques to build an intelligence platform that provides an ethical, AI-driven methodology for identifying under-capitalized founders and unlocking capital.

### Success Criteria
Working web application, risk scoring engine, trajectory output data and model, founder assessment prototype, opportunity heatmaps, executive presentation and documentation, and base Founder Intelligence Platform.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month       | Milestone                | Key Activities                                                                            |
|-------------|--------------------------|------------------------------------------------------------------------------------------|
| Month | Milestone | Key Activities |
| --- | --- | --- |
| September | Data Ingestion, Preprocessing & Baseline Scoring Model | • Ingest and clean multi-source founder and startup datasets (demographics, team metrics, historical funding, market traction).<br>

• Handle missing records, encode categorical attributes, and normalize numerical valuation and growth features.<br>
<br>• Perform Exploratory Data Analysis (EDA) on key success drivers and failure indicators across startup cohorts.<br>
• Train baseline machine learning models (Logistic Regression / Decision Trees) to predict startup viability and funding success. |
| October | Advanced Predictive Modeling & Feature Engineering | • Engineer domain-specific founder intelligence features (serial founder indicators, domain experience fit, team composition diversity, funding velocity).<br>
• Develop advanced ML models (Random Forest, XGBoost, LightGBM) to generate multi-dimensional founder and startup success scores.<br>
• Perform hyperparameter tuning, cross-validation, and evaluate model performance using ROC-AUC, F1-Score, and MAE. |
| November / December | Model Explainability, Interactive Dashboard & Final Deliverables | • Apply model interpretability techniques (SHAP / LIME) to isolate key background and execution factors driving founder ratings.<br>
• Build an interactive Streamlit application allowing investors and advisors to query founder profiles, view risk scores, and inspect key drivers.<br>
• Finalize a clean, reproducible GitHub repository, complete technical documentation, and an executive pitch deck. |

### Stretch Goals

* **Automated Pitch Deck & Document Extraction:** Integrate an LLM/VLM pipeline to parse unstructured startup pitch decks and executive summaries into structured founder intelligence profiles.
* **Investor-Founder Matchmaking Engine:** Build a recommendation module that matches high-potential founder profiles with relevant venture capital firms based on sector alignment, stage preference, and investment thesis.
* **Dynamic Post-Investment Trajectory Tracker:** Develop a time-series monitoring module to track ongoing startup execution (hiring velocity, web traffic, social sentiment) post-evaluation.
> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** USPTO, Tech Hubs, LinkedIn, YouTube, Instagram, trajectory analysis from partner organization  
**Format:** CSV, JSON, Excel  
**Size:** 1gb to 5gb  
**Location:** [Link to dataset or instructions for accessing it]

### Key Details
- Publicly available data from USPTO, Tech Hubs, LinkedIn, YouTube, and Instagram, with trajectory analysis provided by a partner organization. Data types include numerical, categorical, and text in various formats such as CSV/TSV, JSON, Excel, and database exports.
- [Any known limitations or preprocessing needed]
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification, Clustering, Recommendation Systems, Natural Language Processing (NLP), Computer Vision, Time Series Analysis, Deep Learning / Neural Networks, Large Language Models (LLMs)/ Generative AI

**Recommended Libraries:**
- Classification
- Clustering
- Recommendation Systems
- Natural Language Processing (NLP)
- Computer Vision
- Time Series Analysis
- Deep Learning / Neural Networks
- Large Language Models (LLMs)/ Generative AI
- Supervised learning
- Geo location
- Reverse geo-coding
- Heat mapping

**Evaluation Metrics:**
- Accuracy, Precision/Recall, RMSE, BLEU score

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [Link to an article or blog post about the problem domain]
- [Link to an industry report or case study]

**Technical Tutorials:**
- [Link to a free tutorial on the ML technique(s) involved]
- [Link to documentation for a key library or tool]

**Code Examples:**
- [Link to a relevant GitHub repo]
- [Link to a sample implementation or starter code]

**Other:**
- [Links to any additional resources — e.g., papers, videos, podcasts, etc.]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace) or email  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab, VS Code
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).
