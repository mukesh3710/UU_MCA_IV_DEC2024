# UU_MCA_IV_DEC2024

# Loan Data Analysis and Visualization Application

This project is a web-based application that processes loan-related data, generates insights through visualizations, and provides a downloadable PDF report. It is designed for financial institutions and analysts to explore loan approval trends and analyze applicant data.

---

## Features

1. **Data Upload**  
   - Users can upload CSV files containing loan-related data.  
   - A downloadable CSV template is provided for convenience.

2. **Data Processing**  
   - Cleans and preprocesses the uploaded data.  
   - Handles missing values and encodes categorical features.

3. **Data Visualization**  
   - Generates meaningful visualizations such as:  
     - Correlation Matrix  
     - Loan Status Distributions  
     - Income Distributions  
     - Credit History Comparisons  
     - Term vs Loan Status Bar Charts  

4. **PDF Report Generation**  
   - Combines generated visualizations into a single PDF report for easy sharing.

5. **User-Friendly Interface**  
   - Simple, intuitive interface for uploading files and downloading the results.

---

## Technology Stack

- **Backend:** Flask (Python Framework)  
- **Frontend:** HTML, CSS, Bootstrap  
- **Visualization Libraries:** Matplotlib, Seaborn, Plotly  
- **Data Processing:** Pandas, NumPy, scikit-learn  
- **PDF Generation:** PIL (Pillow)

---

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/<your-username>/<repository-name>.git
   cd <repository-name>

2. **Set Up a Virtual Environment (Optional but Recommended - Python Version 3.8.5 ):**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt

4. **Run the Application:**
   ```bash
   python app.py

5. **Access the Application:**
Open a web browser and navigate to http://127.0.0.1:5000.
