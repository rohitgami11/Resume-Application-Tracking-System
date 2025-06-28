# Resume Application Tracking System

An intelligent web application that evaluates resumes against job descriptions using Google's Gemini AI model. This system mimics an advanced Applicant Tracking System (ATS), analyzing resumes and providing actionable insights to improve job application outcomes.

## 🔍 Features

- 📄 Upload and parse PDF resumes
- 🧠 Analyze resume against job descriptions using Gemini AI (Google Generative AI)
- 📊 Output includes:
  - JD match percentage
  - Missing keywords
  - Profile summary tailored to the job description
- 📈 Helps users improve their resumes for better chances in a competitive job market

## 🛠️ Built With

- [Streamlit](https://streamlit.io/)
- [Google Generative AI (Gemini)](https://ai.google.dev/)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/resume-ats-analyzer.git
cd resume-ats-analyzer
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Up Environment Variable

Create a `.env` file in the root directory and add your Gemini API key:

```env
GOOGLE_API_KEY=your_api_key_here
```

### 4. Run the App

```bash
streamlit run main.py
```

## 📂 Project Structure

```
resume-ats-analyzer/
│
├── main.py              # Main application script
├── requirements.txt     # Python dependencies
├── .env                 # (Your environment file - not tracked in version control)
└── README.md           # Project documentation
```

## 📌 Example Use Case

1. Paste a job description into the text area.
2. Upload your resume in PDF format.
3. Get AI-generated feedback:
   - Match percentage with JD
   - Keywords to improve
   - A personalized profile summary

## ⚠️ Note

- Ensure your `.env` file is **not committed** to version control.
- This tool is meant for educational and personal career development purposes.

## 🙌 Acknowledgements

- Google for providing Gemini Generative AI
- Streamlit for making data apps effortless

## 📃 License

This project is open-source and available under the MIT License.

---
