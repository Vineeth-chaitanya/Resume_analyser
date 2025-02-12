Resume Analysis with NLP

Introduction
In this project, we utilize spaCy for entity recognition on 200 resumes and experiment with various Natural Language Processing (NLP) tools for text analysis. The goal is to assist recruiters in screening hundreds of applications within minutes.

Additionally, we have implemented a skills match feature to help hiring managers evaluate candidates efficiently, providing a metric to decide whether to proceed to the interview stage.

Dataset
We use two datasets in this project:
1. Resume Dataset (livecareer.com) – A collection of 2400+ resume examples sourced from livecareer.com.
2. Skills Dataset – A curated list of skills used to create an entity ruler for better resume parsing.

Resume Dataset Details
The dataset contains the following columns:

- ID – Unique identifier and file name for each resume.
- Resume_str – The raw resume text extracted from the document.
- Resume_html – Resume content in HTML format, obtained through web scraping.
- Category – The job category the resume belongs to.

Job Categories Present in the Dataset
The resumes belong to various professional categories, including:

HR, Designer, Information Technology, Teacher, Advocate, Business Development, Healthcare, Fitness, Agriculture, BPO, Sales, Consultant, Digital Media, Automobile, Chef, Finance, Apparel, Engineering, Accountant, Construction, Public Relations, Banking, Arts, Aviation.
