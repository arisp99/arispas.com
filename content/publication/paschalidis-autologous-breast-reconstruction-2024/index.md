---
title: "In Autologous Breast Reconstruction, Machine Learning Models Are Poor Predictors of Post-Surgical Morbidity: A Retrospective Cohort Study on a National Database"
authors: 
- arisp99
- Constantine S. Velmahos
- Giorgio Giatsidis
author_notes:
- "These authors contributed equally to this work."
- "These authors contributed equally to this work."
date: 2024-09-27

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-03

# Publication type.
# Legend: 0 = Uncategorized; 1 = Journal article; 2 = Preprint;
# 3 = Working Paper; 4 = Conference paper; 5 = Oral presentation; 
# 6 = Poster presentation; 7 = Thesis; 8 = Book; 9 = Book Section
publication_types: ["5"]

# Publication name and optional abbreviated publication name.
publication: "Presented at: Plastic Surgery The Meeting"
publication_short: ""

# Abstract and optional shortened version
abstract: "
**Purpose:** In autologous breast reconstruction (ABR), high post-surgical 
morbidity is reported in 20-40% of select patients. Unfortunately, multivariate
logistic regression models and clinically relevant variables with high odds 
ratios, such as age, body mass index (BMI), American Society of Anesthesiology
(ASA) score, and modified frailty index (MFI), predict morbidity with 
insufficient accuracy. As machine learning (ML) has shown impressive predictive
capabilities in several clinical scenarios, we hypothesize that ML may predict
post-surgical morbidity in ABR with higher accuracy than classical statistical
logistic regression models.\n\n
**Methods:** The American College of Surgeons - National Surgical Quality 
Improvement Program (ACS-NSQIP) database was retrospectively queried to 
identify ABR cases from January 2005 to December 2020. The primary outcome was 
to predict the presence of any 30-day post-operative morbidity. This outcome was
a composite of all 18 variables in the ACS-NSQIP that track post-operative 
morbidity. The secondary outcome was to individually predict the 7 complications
with the highest incidence in the cohort: return to operating room, bleeding, 
readmission, superficial infection, wound dehiscence, deep infection, 
organ/space infection (listed in descending incidence). Three ML models 
(Random Forests, XGBoost, and L1-L2-RFE) were compared to one multivariate 
logistic regression (mLR) model and four univariate logistic regression models 
(age, ASA score, BMI, mFI-5). Performance was analyzed using the area under the
curve (AUC).\n\n
**Results:** Of the 25,163 ABR cases identified, 8,330 (33.1%) experienced 
30-day postoperative morbidity. Random Forests, XGBoost, and L1-L2-RFE predicted
postoperative morbidity similarly to the mLR model (AUC: 0.645, 0.643, and 0.653
vs. 0.653, respectively). The difference in AUC between ML and mLR models was
consistently <0.03. Both mLR and ML predicted post-surgical morbidity with >0.10
higher AUC values than any of the four single-factor models, which all showed 
AUC<0.6 (Age: AUC=0.501; ASA score: AUC=0.555; BMI: AUC=0.561; MFI-5: 
AUC=0.5450). Among individual complications, bleeding (L1-L2-RFE: AUC=0.754) and
deep infection (XGBoost: AUC=0.722) were predicted with the highest AUC. For 
each individual complication, the difference in AUC between all models (ML, mLR,
and single-factor) was <0.05.\n\n
**Conclusions:** ML and mLR performed comparably, yet sub-optimally in the 
prediction of post-surgical morbidity in ABR. Single-factor models with commonly
clinically utilized variables were even worse predictors of morbidity. As all 
models achieved low AUC, these models may be limited by current surgical 
database robustness rather than innate predictive capability. Thoughtful design
and granularity of future ABR databases may enhance predictive model 
performance, but further research is warranted.
"
summary: ""

tags: []
featured: false

# Links
# links:
# - name: ""
#   url: """
url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
