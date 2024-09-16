# Nebula Assignment

## Author
Bhaskar Vivek Agarwal

## Overview
This project is a Streamlit application for analyzing resumes based on job descriptions. It uses OpenAI’s GPT-4 model to compare resumes against job descriptions and provides a similarity score and detailed analysis.

## Features
- Upload PDF resumes.
- Enter job description for comparison.
- Filter results based on Top K values and Percentage Criteria.
- View similarity scores and detailed analysis.
- Preview uploaded PDFs directly within the app.

## Project Structure
- `main.py`: The main Streamlit application file.
- `utils.py`: Contains utility functions for interacting with OpenAI API, processing PDFs, and computing embeddings.
- `requirements.txt`: Lists the dependencies required to run the project.
- `.env`: Stores environment variables like the OpenAI API key.

## Requirements
- Python 3.x
- Streamlit
- OpenAI
- LangChain Community
- PyMuPDF
- Pandas
- `python-dotenv`

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/BhaskarBMU/Resume-Ranker-Nebula9.ai.git
   cd your-repo
