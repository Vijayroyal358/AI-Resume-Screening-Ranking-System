
```markdown
# AI Resume Screening & Candidate Ranking System  

This project is a **Streamlit-based web application** that ranks resumes based on their relevance to a given job description using **TF-IDF and Cosine Similarity**.  

## 🚀 Features  
- Upload multiple PDF resumes  
- Extract text from resumes  
- Compute similarity scores using **TF-IDF & Cosine Similarity**  
- Rank resumes based on job description match  
- Display ranking results in a tabular format  

## 📂 Project Structure  
```
AI-Resume-Screening-Ranking-System/
│── Example Resumes/         # Folder containing sample resumes (PDFs)
│── app.py                   # Main Streamlit application file
│── resume_ranking.ipynb     # Jupyter Notebook for development/testing
│── requirements.txt         # Required Python dependencies
│── README.md                # Project documentation (this file)
```

## 🛠️ Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/AI-Resume-Screening-Ranking-System.git  
cd AI-Resume-Screening-Ranking-System
```

### 2️⃣ Create Virtual Environment (Optional but Recommended)  
```bash
python -m venv venv  
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3️⃣ Install Dependencies  
```bash
pip install -r requirements.txt  
```

## ▶️ Running the Application  
Run the Streamlit app:  
```bash
streamlit run app.py  
```
Then, open the **localhost link** shown in the terminal to access the app.  

## 📝 Usage  
1. Enter the **job description** in the text box.  
2. Upload multiple **PDF resumes**.  
3. The system extracts text, computes similarity scores, and **ranks** candidates based on relevance.  
4. Results are displayed in a **sorted table** (higher score = better match).  

## 🛠️ Requirements (Libraries)  
Ensure you have the following libraries installed:  
```bash
streamlit  
PyPDF2  
pandas  
scikit-learn  
```
(These are already included in `requirements.txt`.)

## 🌐 Deployment  
The app is deployed on Streamlit:  
🔗 [Live App](https://ai-resume-screening-ranking-system-ezckk6dgemrjctsegmx29x.streamlit.app/)  

---

## 🤝 Contributing  
Contributions are welcome! If you'd like to contribute, please follow these steps:  
1. Fork the repository.  
2. Create a new branch (`git checkout -b feature/YourFeatureName`).  
3. Commit your changes (`git commit -m 'Add some feature'`).  
4. Push to the branch (`git push origin feature/YourFeatureName`).  
5. Open a pull request.  

## 📄 License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

## 🙏 Acknowledgments  
- **Streamlit** for providing an easy-to-use framework for building web applications.  
- **PyPDF2** for PDF text extraction.  
- **scikit-learn** for TF-IDF Vectorization and Cosine Similarity calculations.  

## 📧 Contact  
For questions or feedback, feel free to reach out:  
- **Email**: vijayroyal358@gmail.com  
- **GitHub**: [Vijayroyal358](https://github.com/Vijayroyal358)  
```
