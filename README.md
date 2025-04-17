# Automated-cv-scorer
This project automates the processing of resumes, extracting and masking personal information, scoring the resumes based on job description (JD) match, and sending feedback emails to applicants.

Features

Resume Processing: Extracts personal details (name, email) and masks them for privacy.

Scoring System: Computes a score based on JD-CV match.

Email Automation: Sends feedback emails with score breakdowns and feedback to applicants.

Logging: Tracks the processing of resumes and email statuses.

Installation
To get started, you'll need to set up a Python environment and install the required dependencies. Follow these steps:

Step 1: Clone the repository

git clone <repository-url>
cd <repository-directory>

Step 2: Set up a virtual environment
Create a virtual environment to isolate the dependencies:

python -m venv venv

Activate the virtual environment:

Windows:

.\venv\Scripts\activate

Install dependencies

Install the required libraries using pip:

pip install -r requirements.txt

Set up environment variables
Create a .env file in the project root directory to store sensitive information (like email credentials):

EMAIL_USER=your_email@example.com

EMAIL_PASS=your_email_password

**Generate an App Password: https://myaccount.google.com/apppasswords**

Make sure to replace your_email@example.com and your_email_password with your actual email credentials.

Note: change folder path in code with your respective path
