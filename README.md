# 📄 NLP Resume Analysis Tool
> *Automating candidate screening with Natural Language Processing*

## 🚀 Overview
In the modern recruitment landscape, HR professionals are inundated with hundreds of resumes daily. This project leverages **Natural Language Processing (NLP)** to automate the screening process, enabling recruiters to analyze, categorize, and extract key insights from resumes in seconds.

By utilizing **spaCy** for advanced Entity Recognition and **Python** for data analysis, this tool transforms unstructured resume text into structured data, visualizing candidate skills and job categories to facilitate data-driven hiring decisions.

## ✨ Key Features
*   **Resume Parsing**: Automatically cleans and extracts text from resumes.
*   **Skill Extraction**: Identification of technical and soft skills using a custom spaCy EntityRuler.
*   **Job Categorization**: Classifies resumes into industry categories (e.g., HR, Engineering, Finance).
*   **Interactive Visualization**: Uses **displaCy** to visually highlight named entities (Skills, Organizations, Dates) directly within the resume text.
*   **Data Insights**: Visual distribution of job categories across the dataset.

## 🛠️ Technologies Used
*   **Python 3.x**
*   **spaCy** (NLP & Named Entity Recognition)
*   **Pandas & NumPy** (Data Manipulation)
*   **Matplotlib & Seaborn** (Data Visualization)
*   **WordCloud** (Text Visualization)
*   **Gensim** (Topic Modeling/Word Vectors)
*   **NLTK** (Text Preprocessing)

## 📂 Project Structure
```
Resume_analysis/
├── Resume/
│   ├── Analyser.ipynb       # Main analysis notebook
│   ├── Resume.csv           # Dataset containing resume text/HTML
│   └── jz_skill_patterns.jsonl # Patterns for skill extraction
├── data/                    # Raw data files
├── requirements.txt         # Project dependencies
└── Readme.txt               # Original project notes
```

## ⚡ Getting Started

### Prerequisites
Ensure you have Python installed. It is recommended to use a virtual environment.

### Installation
1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd Resume_analysis
    ```

2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Download spaCy model**:
    This project uses the large English model for better accuracy.
    ```bash
    python -m spacy download en_core_web_lg
    ```

4.  **Download NLTK data**:
    The notebook will automatically download necessary NLTK data (stopwords, wordnet), but you can also run:
    ```python
    import nltk
    nltk.download(['stopwords', 'wordnet'])
    ```

## 📊 Usage
1.  Navigate to the `Resume` directory:
    ```bash
    cd Resume
    ```
2.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook Analyser.ipynb
    ```
3.  Run the cells to ingest data, process resumes, and view the analysis.

## 📈 Dataset
The project utilizes a dataset sourced from **LiveCareer**, consisting of 2400+ resumes across 24 distinct job categories including:
*   Information Technology
*   Finance
*   Engineering
*   Healthcare
*   Sales
*   ...and more.

## 🤝 Contributing
Contributions are welcome! Please perform the following steps:
1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.


