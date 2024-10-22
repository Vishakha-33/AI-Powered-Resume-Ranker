# AI-Powered-Resume-Ranker
This project is an AI-based web application that ranks resumes based on the given job description using BERT embeddings and keyword matching.

Features:
1.Upload multiple resumes (in PDF format).
2.Extracts text from resumes using PyPDF2.
3.Utilizes BERT embeddings to compute similarity between resumes and job descriptions.
4.Ranks resumes based on similarity to job descriptions, with penalties for irrelevant keywords.
5.Outputs the ranked resumes with a similarity score.

Technologies Used:
1.Flask for the web framework.
2.BERT (via Hugging Face Transformers) for generating semantic embeddings.
3.PyPDF2 for extracting text from resumes.
4.Regular expressions for extracting names and emails.
5.NumPy and Scikit-learn for similarity computation.
6.HTML/CSS for front-end.


Installation Instructions:

1.Clone the repository:
git clone https://github.com/yourusername/ai-resume-ranker.git
cd ai-resume-ranker

2.Install the required dependencies:
pip install -r requirements.txt

3.Run the Flask app:
python app.py

4.Open your browser and navigate to http://127.0.0.1:5000 to use the app.
