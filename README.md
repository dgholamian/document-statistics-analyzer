# Document Statistics Analyzer

## Overview
The **Document Statistics Analyzer** is a Python-based tool designed to extract and analyze linguistic and structural features from text documents. It supports multiple file formats (PDF, DOCX, TXT) and provides detailed insights at the word, sentence, paragraph, and document levels. The tool generates comprehensive reports in Markdown, HTML, or PDF formats, complete with visualizations like word clouds, histograms, bar charts, and sentiment heatmaps. Reports and visualizations are bundled into a downloadable ZIP archive for easy sharing.

This project leverages libraries such as NLTK, spaCy, TextBlob, and Gradio to perform natural language processing, sentiment analysis, and interactive user interface creation.

## Features
- **File Support**: Processes PDF, DOCX, and TXT files.
- **Word-Level Analysis**:
  - Tokenization and Part-of-Speech (POS) tagging
  - TF-IDF keyword extraction
  - N-gram frequency analysis
  - Keyword co-occurrence
  - Lexical diversity (Type-Token Ratio)
  - Stop word ratio and average word length
- **Sentence-Level Analysis**:
  - Sentence count and length distribution
  - Average sentence length
  - Sentence-level sentiment analysis
- **Paragraph-Level Analysis**:
  - Paragraph count
  - Sentence count per paragraph
  - Average sentences per paragraph
- **Document-Level Analysis**:
  - Total word count
  - Readability scores (Flesch Reading Ease, Flesch-Kincaid Grade)
  - Named Entity Recognition (NER)
  - Overall document sentiment
  - Punctuation frequency
- **Visualizations**:
  - Word cloud
  - Sentence and paragraph length histograms
  - POS tag distribution bar chart
  - Sentiment heatmap
- **Report Generation**:
  - Customizable reports in Markdown, HTML, or PDF
  - Executive summary with key insights
  - Embedded visualizations
  - ZIP archive for report and images
- **User Interface**:
  - Interactive Gradio interface for file upload and report generation
