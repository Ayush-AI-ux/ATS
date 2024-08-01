# Application Tracking System (ATS) 💻

Welcome to the Application Tracking System (ATS)! This tool helps you improve your resume by matching it against job descriptions. It provides insights into missing keywords and gives a profile summary to help you stand out in a competitive job market.

## Features

- Upload your resume in PDF format.
- Provide a detailed job description.
- Get an analysis of your resume's match with the job description.
- Receive insights on missing keywords.
- Get a summary of your profile.

## Installation

To get started with the Application Tracking System, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Ayush-AI-ux/ATS.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ATS
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Create a `.env` file in the project root and add your API key:
    ```env
    GEMINI_API_KEY=your_gemini_api_key
    ```

## Usage

To run the Application Tracking System, use the following command:
```bash
streamlit run app.py
