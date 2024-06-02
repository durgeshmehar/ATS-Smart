# ATSmart

ATSmart is a web application designed to assist users in evaluating their resumes based on a given job description. The application utilizes advanced technologies, including Google's GenerativeAI with the latest model Gemini Pro, to provide accurate assessments.

## Features

- **Resume Evaluation**: Upload your resume and get an evaluation based on a specific job description.
- **Advanced AI**: Leverages Google's GenerativeAI Gemini Pro model for precise and intelligent assessments.
- **User-Friendly Interface**: Simple and intuitive interface for ease of use.

## Technologies Used

- **Django**: Backend framework for building the web application.
- **Streamlit**: For creating interactive and data-driven UI components.
- **Google GenerativeAI Gemini Pro**: Advanced AI model for resume evaluation.
- **PyPDF2**: Python library that allows users to manipulate and extract information from PDF files.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/atsmart.git
    cd atsmart
    ```

2. **Set Up Virtual Environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run Migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Run the Development Server**:
    ```bash
    python manage.py runserver
    ```

6. **Run Streamlit App**:
    ```bash
    streamlit run streamlit_app.py
    ```
    
## Acknowledgements

- **Google GenerativeAI Gemini Pro**: For providing the AI model used for resume evaluation.
- **Django**: For the robust web framework.
- **Streamlit**: For creating interactive UI components.

---

Feel free to explore, use, and contribute to ATSmart. For any issues or feature requests, please open an issue in the repository.

