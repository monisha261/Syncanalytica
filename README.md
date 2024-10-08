
# **SyncAnalytica: Real-Time Data Collaboration & Analytics Tool**

**SyncAnalytica** is a platform that streamlines real-time collaboration and data analysis. It simplifies the process of ingesting, processing, visualizing, and generating insights from datasets, with features powered by machine learning and NLP models.

## **Features**
- Upload and process **.csv** or **.xlsx** files for data analysis.
- Clean, transform, and preprocess data efficiently.
- Apply **Machine Learning** models (Random Forest, SVM) for predictive insights.
- Utilize **NLP** for text analysis and report generation using **BERT/GPT** models.
- Visualize data through interactive charts, graphs, and word clouds.
- Generate summaries using the **Gemini API**.
- Analyze data visualizations and generate insights with **Gemini Vision**.

## **Project Structure**

├── app/ # Main application directory │ 
├── backend/ # Backend API and data handling │ 
├── frontend/ # Frontend with React and Streamlit │ 
├── models/ # Machine learning models (Random Forest, SVM) │ 
└── nlp/ # NLP models (BERT, GPT) ├── data/ # Sample datasets for testing 
├── requirements.txt # Python dependencies ├── README.md # Project documentation 
└── LICENSE # License information


## **Getting Started**

### **Prerequisites**
- **Python 3.8+**
- **pip** (Python package manager)
- **Node.js** (for frontend React components)
  
### **Installation**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/guru936/SyncAnalytica.git
   cd SyncAnalytica
   
### **Install backend dependencies:**
    ```bash

    pip install -r requirements.txt

### **Install frontend dependencies:***
    ```bash

    cd frontend
    npm install

### **Run the Application**

   1. **Start the backend (Streamlit & Flask):**
    ```bash

    cd backend
    streamlit run app.py

**Run the frontend (React):**
    ```bash

    cd frontend
    npm start

### **Using SyncAnalytica**

    Upload your .csv or .xlsx file through the interface.
    Follow the data ingestion and cleaning steps.
    Explore visualizations and insights.
    Generate and download reports in PDF format.

### **Contributing**

We welcome contributions to enhance SyncAnalytica! Please open an issue or submit a pull request.
Steps to Contribute:

    Fork the repository.
    Create a new feature branch.
    Commit your changes.
    Open a pull request.

### **References**

    Pandas Documentation: Pandas Docs
    Scikit-learn: Scikit-learn Docs
    Hugging Face (BERT/GPT Models): Hugging Face Docs
    Streamlit Documentation: Streamlit Docs
    RAG Model: RAG Paper

### **License**

This project is licensed under the MIT License - see the LICENSE file for details.
