# AI Based Crop Disease Detection System

This is a mini AI/NLP project that detects crop diseases based on symptoms typed by the user.

**What This Project Does**
- User types the symptoms they see on the plant (like spots, color change, wilting)
- The system tells the Disease, Crop, Confidence Score, and Solution
- No images are used, only text-based symptoms

**Tools Used**
- Python
- Pandas (to read and manage the dataset)
- NumPy (for calculations)
- Matplotlib and Seaborn (for graphs)

**Dataset**
- A CSV file with 4 columns: Crop, Disease, Symptoms, Solution

**How It Works**
1. Symptom text is cleaned (lowercase, remove symbols, tokenize, remove stopwords, stemming)
2. Text is converted into numbers using TF-IDF
3. User's input is compared with the dataset using Cosine Similarity
4. Best matching disease, crop, and solution are shown with a confidence score

**Features**
- User can type their own symptoms and get instant results
- Sample test cases are shown with results and graphs

**Conclusion**
This project uses basic NLP techniques like tokenization, TF-IDF, and cosine similarity to build a simple disease detection system using only symptom text.
