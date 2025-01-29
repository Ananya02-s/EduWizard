# README.md

## EduWizard - Your Personal Educational Assistant

EduWizard is a Streamlit-based web application that utilizes Google Generative AI (Gemini Pro) to provide educational assistance on various topics. 
It allows users to enter questions and receive responses in real-time.

### Features

- Subject-specific assistance in Math, Science, History, and more.
- Homework help for detailed problem-solving steps.
- Concept explanations for complex topics.
- Resource suggestions for further reading and study materials.

### Getting Started

1. **Clone the Repository**
git clone https://github.com/Ananya02-s/EduWizard.git


2. **Navigate to the Project Folder**
cd EduWizard


3. **Install Dependencies**
pip install -r requirements.txt


4. **Set Environment Variables**  
Create a `.env` file in the root directory and add your Google API key:
GOOGLE_API_KEY=your_google_api_key


5. **Run the Application**
streamlit run eduWiz_sans.py


### Usage

- Open the Streamlit app in your browser.
- Enter any educational query in the text box and click "Get Answer."
- The AI will provide a response, and you can view the full chat history below.
