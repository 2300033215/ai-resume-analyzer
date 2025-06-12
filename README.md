The ai resume analyzer the content and structure of a resume and provides constructive feedback to help improve job readiness. The analysis is performed using a custom AI agent that reviews the resume for missing skills, formatting issues, and overall strength.

🔍 Key Features
PDF Upload and Parsing: Users can upload their resume in PDF format; the script extracts the text using PyPDF2.

AI-Powered Analysis: A custom agent built with pydantic_ai and the groq:llama3-8b-8192 model performs the review.

Resume Insights:

Identifies missing technical and soft skills

Detects formatting issues

Rates the job-readiness score (out of 10)

Provides suggestions for improvement

🛠 Technologies Used
Python

PyPDF2 – For extracting text from PDF

pydantic_ai – To define and run the AI agent

Groq API – For LLaMA 3 model inference

Google Colab – For interactive execution

nest_asyncio – To enable async in Colab
