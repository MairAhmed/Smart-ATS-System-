# Smart ATS - Resume Evaluator

Smart ATS is a web application built using Streamlit that leverages Google's Generative AI (Gemini) to evaluate resumes against job descriptions, acting as an Application Tracking System (ATS). The app extracts text from a PDF resume and compares it with a provided job description, offering a matching percentage, missing keywords, and a profile summary.


## Features
- **Resume Evaluation**: The app acts like an ATS and evaluates a resume against a provided job description.
- **Generative AI Integration**: Uses Google's Gemini API to analyze the resume and return insights such as matching percentage, missing keywords, and profile summary.
- **PDF Parsing**: Extracts text from uploaded PDF resumes.
- **Interactive UI**: Built using Streamlit for user interaction, allowing users to upload resumes and paste job descriptions.

## Installation

Follow these steps to set up the project on your local machine.

### Prerequisites
- Python 3.7+
- A Google Cloud account with access to the Gemini model API.
- API key from Google Cloud for Generative AI (Gemini).

### Steps to Install and Run the Application

1. **Clone the Repository**:
   Begin by cloning the repository from GitHub:
   ```bash
   git clone https://github.com/MairAhmed/<your-repository>.git
   cd <your-repository>

# Create a virtual environment
    python -m venv venv

# Activate the virtual environment
# For macOS/Linux
    source venv/bin/activate
# For Windows
    venv\Scripts\activate


# Install Dependencies:
After setting up the virtual environment, install the required dependencies using the requirements.txt file:


      pip install -r requirements.txt


# Configure Environment Variables: 
You need to securely configure your environment variables to store the Google API key:

Create a .env file in the root directory of the project.

Add the following content to the .env file

      GOOGLE_API_KEY=your_api_key_here


# Run the Application: 
Start the Streamlit app by running the following command:


     streamlit run app.py





   
