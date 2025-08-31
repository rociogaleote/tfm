# Accompanying Code for Master’s Thesis - Not-so-Great Expectations: Analyzing Gender, Genre and Reader Bias in Popular Fiction Using Computational Methods
By Rocío Galeote

# Project summary

This paper investigates the presence and nature of gender bias in the reception of books in Mystery and Romance genres, analyzing how author gender influences reader evaluations in online book reviews. The primary data source for this analysis are two datasets scraped by Mengting Wan and Julian McAuley in late 2017, extracted from publicly available reviews and book metadata. 
Focusing on the said two genres, this study examines whether an author's gender systematically affects the ratings, descriptive language, and overall sentiment of reviews. Three specific hypotheses are tested: 

(H1) that author gender influences book review ratings
(H2) that author mentions and the adjectives used to describe them in book reviews differ significantly across genders
(H3) that holding review rating constant, reviews of male-authored and female-authored books have different sentiment scores 

By employing a multi-faceted approach that combines quantitative rating analysis with natural language processing of review content, this research aims to explore whether gender bias exists in how readers perceive and engage with novels across different fiction genres and assess whether the gender of an author influences how their books are rated and reviewed, especially in literary genres hegemonically associated with the opposite gender.The findings are expected to contribute to a deeper understanding of how gender stereotypes shape literary evaluation and reader engagement in the digital age.

# List of code documents and their description
For clarity, the code has been separated into different RMDs, depending on the stage of the analysis:
- Data processing: code for pre-processing the original datasets.
- Data curation: code for stages of data removal, genderization and language detection
- H1: code for testing hypothesis 1
- H2: code for testing hypothesis 2
- H3: code for testing hypothesis 3

# List of dataset files and their description
Due to intermediate API procedures, the original dataset as well as further versions are extracted into RData and CSV formats for review, if needed. Beware: the size of the datasets requires *extensive* memory usage in RStudio when incorporating the files into the environment.

- mystery_clean/ romance_clean: datasets after pre-processing
- mystery_final/ romance_final: datasets after data curation
- mystery_author_mentions/ romance_author_mentions: subset of mystery_final and romance_final for H2 and H3

Due to size constraints, all datasets can be found here: https://drive.google.com/drive/folders/1w8wFP_TfiGwVEsP--WU6R42xoTmAdHlt?usp=sharing. For inquiries or errors downloading said datasets, please contact 100431024@alumnos.uc3m.es

# Disclaimer
This project was developed exclusively for academic purposes as part of my final thesis for the Masters Degree in Computational Social Science at Carlos III University. The code and materials provided are intended for research and educational use only. Commercial use is strictly prohibited. For permissions or inquiries, please contact the administrator.
