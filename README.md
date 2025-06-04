# AI_Health_Assistant

An intelligent healthcare assistant built using AI technologies to help users with symptoms analysis, disease prediction, precautions, and diet recommendations.

🚀 Features

🤖 Symptom-based disease prediction

💊 Precautions and dietary suggestions

🗣️ Interactive chatbot interface

📈 Scalable backend with Flask

🐳 Docker support for deployment

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript (or React, if used)

Backend: Python (Flask)

ML/NLP: Scikit-learn, Pandas, NLTK

Database: SQLite / MongoDB (if used)

Deployment: Docker

💻 How to Run on Your Laptop

Step 1: Clone the Repository

```
git clone https://github.com/Akhila-1703/AI_Health_Assistant.git
cd AI_Health_Assistant
```

Step 2: Set Up the Environment

If using Python:

```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Step 3: Set Environment Variables

Create a .env file by copying .env.example and filling in required values:

```
cp .env.example .env
```
Edit .env file and update settings (API keys, DB URLs, etc.).

Step 4: Run the App

```
python app.py
```

Visit http://localhost:5000 in your browser.

🐳 Docker (Optional)

If you prefer to run with Docker:

```
docker build -t ai-health-assistant .
docker run -p 5000:5000 ai-health-assistant
```

📁 Project Structure

```
AI_Health_Assistant/
│
├── backend/            # Flask app and ML logic
├── frontend/           # HTML/CSS/JS files
├── scripts/            # Preprocessing or training scripts
├── tests/              # Unit tests
├── .env.example        # Template for environment variables
├── requirements.txt    # Python dependencies
└── README.md           # This file
```

✅ To Do

 Add authentication (login/signup)

 Improve chatbot UX

 Add support for multiple languages

🙌 Contributing

Fork the repository

Create a new branch (git checkout -b feature-xyz)

Make changes and commit (git commit -m 'Add xyz')

Push to your fork (git push origin feature-xyz)

🛠️ Found a bug? Have a feature request? Feel free to open an issue or submit a pull request.

📬 For questions or feedback, email: akhiladhachepally@gmail.com 

🙏 Thank You  for using this Application!
