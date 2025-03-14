# Resume Categorization System

A machine learning application that automatically categorizes resumes/CVs into relevant job categories using Natural Language Processing (NLP) techniques.

## Overview

This application allows users to upload their resume/CV, and uses a trained ML model to analyze the content and categorize it into appropriate job categories. The system leverages NLP to extract meaningful information from unstructured text data in resumes.

## Features

- **Resume Upload**: Simple interface for users to upload their resume documents
- **Text Extraction**: Automatically extracts text from various document formats (PDF, DOCX, etc.)
- **NLP Processing**: Applies text preprocessing, feature extraction, and classification using NLP techniques
- **Category Classification**: Classifies resumes into predefined job categories
- **Results Export**: Users can download categorization results as CSV files
- **Interactive UI**: User-friendly interface built with Streamlit

## Technology Stack

- Python
- Streamlit (for web interface)
- Natural Language Processing (NLTK, spaCy)
- Machine Learning (scikit-learn)
- PDF and document parsing libraries

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/resume-categorization-system.git
cd resume-categorization-system
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to `http://localhost:8501`

3. Upload a resume/CV through the interface

4. View the categorization results

5. Download results as CSV by clicking the download button

## Model Information

The system uses a machine learning model trained on a diverse dataset of resumes. The model processes the text using:
- Text preprocessing (tokenization, stop word removal, lemmatization)
- Feature extraction (TF-IDF, word embeddings)
- Classification algorithms

## Project Structure

```
├── app.py                # Streamlit application
├── model/                # Trained model files
├── utils/                # Utility functions
│   ├── preprocessor.py   # Text preprocessing utilities
│   ├── extractor.py      # Feature extraction code
│   └── classifier.py     # Classification functionality
├── data/                 # Training data (if included)
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

## Future Improvements

- Add support for more document formats
- Implement more detailed subcategory classification
- Improve accuracy with more training data
- Add confidence scores for predictions
- Incorporate user feedback for model improvement

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
