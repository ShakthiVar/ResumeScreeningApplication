# Resume Screening Application

Resume Screening Application  is a web application that allows users to upload resumes in PDF format, enter keywords, and then parse and score the resumes based on the matching keywords.

## Features

- **Keyword Entry:** Users can enter individual keywords or a space-separated list.
- **Resume Upload:** Resumes in PDF format can be uploaded for parsing.
- **Parsing and Scoring:** The application parses the resumes and scores them based on keyword matches.
- **Review Results:** Users can review the parsed results, including the score, filepath, keywords, and matching words.

## Prerequisites

- Python 3.x
- Flask
- Flask-WTF
- PyPDF2

## Getting Started

1.Clone the Repository

     git clone https://github.com/yourusername/ResumeScreeningApplication.git
     cd ResumeScreeningApplication
  

2. Install dependencies:

       pip install -r requirements.txt
  

3. Run the application:

       python main.py


## The application will be accessible at http://127.0.0.1:5000 in your web browser.


## Demo Video

https://github.com/ShakthiVar/ResumeScreeningApplication/assets/92375087/3e6be8ec-08fe-4b0f-bbf3-a78e2f0a9608

## Usage

1. Access the web application in your browser.
2. Enter keywords individually or as a space-separated list.
3. Upload a resume in PDF format.
4. Click the "Parse" button to parse and score the resume.
5. Review the results on the "Review" page.

   ## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new pull request.
