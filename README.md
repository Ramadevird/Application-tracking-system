# Application-tracking-system
This project is an Applicant Tracking System (ATS) developed using Gemini AI for analyzing resumes against job descriptions. Here's a breakdown of its functionality:

Environment Setup: The project uses the Streamlit framework for creating a user interface. It also utilizes the dotenv library for loading environment variables and pdf2image for converting PDF files to images.

Gemini AI Integration: Gemini AI is integrated into the project for generating responses based on input prompts. The google.generativeai module is used for this purpose, and the API key is fetched from environment variables.

Resume Analysis: Users can input job descriptions and upload resumes (in PDF format) for analysis. The system provides three main functionalities:

Evaluation against Job Description: Users can receive feedback on how well a resume aligns with a job description. The system highlights strengths, weaknesses, and overall alignment.

Skill Improvement Recommendations: Users receive suggestions on skills they can improve based on their resume and the job description. This includes guidance on how to enhance their skills effectively.

Percentage Match: The system calculates the percentage match between a resume and a job description. It provides both the percentage match and highlights keywords missing from the resume.

User Interaction: Users interact with the system through text areas for inputting job descriptions, uploading resumes, and buttons for triggering different analysis functionalities.

Response Display: The system displays the generated responses as subheaders followed by the respective analysis text.

Overall, this project aims to assist HR professionals and job seekers in efficiently evaluating resumes, identifying areas for improvement, and gauging the suitability of candidates for specific job roles.
