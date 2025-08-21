# Flask Project

## Project Overview
This project is a Flask web application designed to collect, store, and analyze user information.  
The application connects to a **MongoDB database** where data is securely stored.  
It then performs basic analysis on the collected data and automatically generates results in a **PowerPoint presentation format** for reporting purposes.  

This project demonstrates skills in:
- Flask web development  
- Database integration with MongoDB  
- Data analysis and processing  
- Automated presentation/report generation  

---

## How the Project Works

1. **User Input**  
   - The Flask app provides a simple web form where users can enter information (e.g., survey data, feedback, or records).  

2. **Database Storage**  
   - Once submitted, the data is stored in a MongoDB collection.  
   - This ensures persistence and allows for multiple entries from different users.  

3. **Data Analysis**  
   - The stored data is processed and analyzed.  
   - The analysis may include summaries, counts, or visual insights depending on the dataset collected.  

4. **Presentation Generation**  
   - After analysis, the results are automatically exported into a **PowerPoint (.pptx)** file.  
   - The generated slides contain both the data insights and visual representation, making it easy to present.  

---

## How to Run Locally
1. Install Python (3.8 or higher).  
2. Install project dependencies:  
   ```bash
   pip install flask pymongo python-pptx


