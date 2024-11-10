# ATS_RESUME_CHECKER


# Smart ATS Resume Checker

## Overview

The Smart ATS Resume Checker is a Stream lit application designed to help job seekers improve their resumes by evaluating them against a given job description. The application leverages Google's Generative AI to provide insights on how well a resume matches the job description, identifies missing keywords, and offers a profile summary.

## Features

- **Resume Evaluation**: Analyzes the resume against the job description to determine the match percentage.
- **Missing Keywords**: Identifies keywords that are missing from the resume but are present in the job description.
- **Profile Summary**: Provides a summary of the resume based on the job description.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher
- Google Generative AI API key
- Streamlit
- PyPDF2
- python-dotenv

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ravivarmanr26/ATS_RESUME_CHECKER.git
   cd ATS_RESUME_CHECKER


Set up a virtual environment (optional but recommended):

bash
Copy
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy
pip install -r requirements.txt
Set up your environment variables:

Create a .env file in the root directory of the project and add your Google API key:

env
Copy
GOOGLE_API_KEY=your_google_api_key_here
Usage
Run the Streamlit app:

bash
Copy
streamlit run app.py
Open your web browser and go to http://localhost:8501 to access the application.

Upload your resume in PDF format and paste the job description in the provided text area.

Click the "Submit" button to get the evaluation results.

Example Output
The application will return a JSON-like string with the following structure:

json
Copy
{
  "JD Match": "85%",
  "MissingKeywords": ["Python", "Machine Learning"],
  "Profile Summary": "A skilled software engineer with experience in web development and data analysis."
}
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you encounter any problems or have suggestions for improvements.

License
This project is licensed under the MIT License. See the LICENSE file for details.
