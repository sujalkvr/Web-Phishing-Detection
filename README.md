# Secure-Web-Phishing-Detection

This project is a web-based application designed to detect phishing websites using a trained machine learning model. Users can input URLs to get an instant prediction about whether the website is safe or suspicious. It also offers dataset upload functionality for previewing data and visual performance analysis.

🚀**Features**
URL-based detection: Submit any URL and get its safety prediction.

Dataset upload: Upload CSV datasets to preview in tabular form.

Interactive charts: Visualize insights from the dataset.

Login page: Basic login functionality (placeholder).

Performance analysis: View recall, F1, precision, and confusion matrix.

Fully responsive front-end with Bootstrap, custom CSS, and JavaScript.

🗂️ **Project Structure**

Detection of Phishing Websites/    # Root directory containing the entire phishing website detection project
├── __pycache__/                  # Python's compiled bytecode cache directory
├── test_data/                    # Directory containing test datasets for model validation
├── templates/                    # Directory containing HTML templates for the web interface
├── static/                       # Directory for static web assets
│   ├── lib/                      # External libraries and dependencies
│   ├── js/                       # JavaScript files for frontend functionality
│   ├── img/                      # Image assets used in the web interface
│   └── css/                      # Stylesheet files for web page styling
├── model/                        # Directory containing model-related files
├── requirements.txt              # Python package dependencies list
├── app.py                        # Main Flask application file
├── Accuracy.txt                  # File containing model accuracy metrics
├── upload.csv                    # Dataset file for training/testing
├── model.pkl                     # Serialized machine learning model
└── feature.py                    # Python script for feature extraction and processing

⚙️ Setup Instructions
Clone the repository:
git clone https://github.com/<your-username>/phishing-website-detection.git
cd phishing-website-detection

Install dependencies:
pip install -r requirements.txt

Run the app:
python app.py

Open in browser:
Visit http://127.0.0.1:5000 to access the application.

🔍 Technologies
Backend: Flask (Python)

Frontend: HTML, CSS (Bootstrap), JavaScript (jQuery, Google Charts)

ML/DS: Scikit-learn, Pandas, Numpy

Web scraping & utilities: BeautifulSoup, Requests, Whois, Google Search

📌 Key Points
The ML model (model.pkl) is loaded using pickle and used to predict URL safety.

Uploaded datasets must be in .csv format.

Login feature is a placeholder – consider real authentication for production.

All HTML templates are customizable for better UI/UX.

🤝 Contributions
Feel free to fork this repo, create pull requests, or raise issues to improve or fix the project!
