# AI-Based Question Paper Generator

## Overview

The AI-Based Question Paper Generator is a tool designed to streamline the process of creating question papers by leveraging AI. This project uses a chatbot trained on previous years' question papers and other educational resources (PDFs). The bot generates unit-wise question papers with specific mark distributions, saving educators time and effort.

## Features

1. AI-Powered Chatbot:

- Trained on educational datasets, including PDFs and previous question papers.
- Generates unit-specific questions.

2. Customizable Mark Distribution:

- Produces a 60-mark question paper with 5 questions (12 marks each).
- Each main question consists of two sub-questions (6 marks each).

3. Unit-Wise Question Paper Generation:

Questions are organized based on the units covered in the syllabus.

4. User-Friendly Flask Application:

Simple interface to upload training materials and retrieve generated papers.

5. Efficient Backend Processing:

Ensures accurate and logical question generation.


## System Requirements

Programming Language: Python 3.8 or above

Framework: Flask

Libraries:

- Natural Language Toolkit (NLTK)
  PyPDF2
- GeminiAI GPT (or other language models)
- vector database (for database management)
- Pandas, NumPy (for data processing)

Database: vector database 

## Installation
1. Clone the Repository:

git clone https://github.com/your-repo/ai-question-paper-generator.git  
cd ai-question-paper-generator  

2. Set Up Virtual Environment:

python -m venv venv  
source venv/bin/activate  # For Linux/MacOS  
venv\Scripts\activate  # For Windows  

3. Install Dependencies:

pip install -r requirements.txt  

4. Run the Application:

python app.py  

## Usage

1. Train the AI:

Upload PDFs or previous question papers through the application interface.
The chatbot processes these files and learns from the content.

2. Generate Question Papers:

Specify the unit(s) and mark distribution.
Click "Generate" to create a customized question paper.

3. Download the Generated Paper:

Save the output in a preferred format (PDF, DOCX).



## How It Works

1. Input: Upload training materials (PDFs, previous question papers).
2. Processing: The system extracts key topics, patterns, and question formats using NLP techniques.
3. Output: The AI generates a question paper matching the specified criteria.

## Future Enhancements

1. Add support for multiple exam formats (MCQs, short answers, etc.).
2. Enable multi-language support for regional examinations.
3. Integrate with Learning Management Systems (LMS).
4. Advanced AI models for improved question diversity.