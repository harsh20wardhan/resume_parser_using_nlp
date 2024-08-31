# 📄 Resume Parser Using NLP

Welcome to the **Resume Parser using NLP** project! This repository contains a tool that extracts and structures information from resumes using Natural Language Processing (NLP). 🧠

## 🚀 Project Overview

Hiring processes often involve sifting through numerous resumes to find the right candidates. This project aims to automate the extraction of key information such as name, contact details, skills, experience, and education from resumes, making the hiring process more efficient.

### 🌟 Features

- **Data Extraction:** Extracts key details like name, contact information, skills, work experience, and education from resumes.
- **NLP Techniques:** Utilizes various NLP techniques such as tokenization, named entity recognition (NER), and regex for information extraction.
- **Multiple Formats:** Supports parsing resumes in different formats like PDF and DOCX.
- **Structured Output:** Outputs structured data in a JSON format for easy integration with other systems.

## 🛠️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/harsh20wardhan/resume_parser_using_nlp.git
cd resume_parser_using_nlp
```

### 2. Install dependencies

Ensure you have Python 3.x installed. Then, install the required packages using pip:

```bash
pip install -r requirements.txt
```

### 3. Run the project

To start parsing resumes, run:

```bash
python parser.py --input path/to/resume.pdf --output output.json
```

Replace `path/to/resume.pdf` with the path to the resume file you want to parse, and `output.json` with the desired output file.

## 📊 Usage

- **Input Files:** Place your resume files in the `input/` directory or specify their path.
- **Output Files:** Parsed data will be saved in the `output/` directory or at the path you specify.
- **Customization:** Modify the `config.yaml` file to adjust the parsing settings.

## 📈 Results

The parser extracts information with a high level of accuracy, structuring the data into a JSON format that can be easily used in other applications or systems.

## 🤝 Contributing

We welcome contributions to improve the parser and add new features! Feel free to fork the repository, make your changes, and submit a pull request.

## 📬 Contact

For any questions, suggestions, or feedback, feel free to reach out to me via [LinkedIn](https://www.linkedin.com/in/harsh20wardhan/) or open an issue.
