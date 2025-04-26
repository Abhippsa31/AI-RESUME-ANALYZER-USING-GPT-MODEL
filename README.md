# 🤖 AI Resume Score Analyzer GPT model

This AI-powered Resume Analyzer uses **OpenAI's GPT-4** and **Natural Language Processing (NLP)** to parse resumes, extract skills, score resumes, and recommend personalized learning resources like YouTube courses. It provides both **LLM-based feedback** and **NLP-based skill extraction**, making it a powerful tool for improving your resume. Built with **Streamlit** for an interactive web interface.

---

## 🚀 Features

- 📄 Upload and analyze PDF resumes
- 🧠 Extract skills using NLP (`pyresparser`)
- 🧠 Analyze content with GPT-4 and suggest improvements
- 📊 Score resumes and provide actionable improvement tips
- 🎯 Recommend skill-based YouTube video courses
- 📁 Admin and User views
- 🔗 Integrated with MySQL to save user data
- 🧠 ATS Optimization Suggestions (using GPT-4)
- 🎯 Job description matching (optional)

---

## 🧰 Tech Stack

- Python 🐍
- Streamlit 🌐
- OpenAI GPT-4 API 🤖
- pyresparser (NLP) 🧠
- spaCy, NLTK, pandas, NumPy
- MySQL (via `pymysql`)
- YouTube video embedding

---

# 🧠 GPT-4 Resume Content Analyzer

This project integrates **OpenAI's GPT-4 model** for resume analysis. The LLM evaluates:

- Resume structure
- Grammar and language clarity
- Content relevance to job descriptions
- Readability and overall professional tone

### 📌 Sample GPT-4 Prompt

```python
prompt = f"""
Analyze the following resume and provide detailed feedback for improvements in structure, grammar, ATS-compatibility, and content relevance:

{resume_text}
"""
{
  "Summary": "Consider adding measurable accomplishments.",
  "Experience": "Include more action verbs like 'led', 'developed', and 'optimized'.",
  "Skills": "Add skills relevant to your target job role.",
  "Score": 82,
  "Suggestions": [
    "Quantify results wherever possible.",
    "Rearrange skills section above education.",
    "Fix formatting inconsistencies in bullet points."
  ]
}
📁 AI-resume-analyzer/
├── app.py                # Main Streamlit frontend
├── Courses.py            # Skill-based YouTube course recommendations
├── gpt_analyzer.py       # GPT-4 resume feedback logic
├── resume_parser.py      # Resume text extractor and skill parser
├── requirements.txt      # Python dependencies
├── Uploaded_Resumes/     # Folder to store uploaded resumes
├── logo/                 # Logo used in the app
└── .venv/                # Python virtual environment (optional)
# Clone the repository
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer

# Install dependencies
pip install -r requirements.txt

# Add your OpenAI API key
export OPENAI_API_KEY='your-api-key'
🙌 Acknowledgements
pyresparser

OpenAI GPT-4

Streamlit Community
📬 Contact
For questions, suggestions, or collaborations, feel free to reach out:
📧 rimun390@gmail.com

MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell     
copies of the Software, and to permit persons to whom the Software is         
furnished to do so, subject to the following conditions:                       

The above copyright notice and this permission notice shall be included in    
all copies or substantial portions of the Software.                           

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR    
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,      
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE   
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER        
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN     
THE SOFTWARE.
