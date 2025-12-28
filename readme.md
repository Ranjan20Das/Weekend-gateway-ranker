# Weekend Destination Recommendation System 🧳🌍

## 📌 Project Overview
This project recommends the **top weekend travel destinations** based on multiple factors such as time required to visit, user ratings, popularity, cost, and accessibility.  
The recommendation is **dataset-driven** and implemented using **Python and Pandas** in **Google Colab**.

The system takes a **Source City** as user input and ranks destinations using a **weighted scoring algorithm**.

---

## 🎯 Objectives
- To analyze tourism data using Python and Pandas
- To rank weekend destinations based on multiple criteria
- To build a simple rule-based recommendation system
- To practice data preprocessing and feature engineering

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **Google Colab**
- **Git & GitHub**

---

## 📂 Dataset Description
The dataset **Top Indian Places to Visit.csv** contains the following important attributes:

- City  
- Place Name  
- Time needed to visit (in hours)  
- Google review rating  
- Entrance Fee (INR)  
- Airport within 50km radius  
- Weekly Off  
- Significance  
- DSLR Allowed  
- Number of Google reviews (in lakhs)  
- Best Time to Visit  

---

## ⚙️ Methodology / Algorithm
1. User enters a **Source City**
2. Destinations from other cities are considered
3. Categorical values are converted into numerical scores
4. A **weighted score** is calculated using:
   - Google Rating
   - Popularity (number of reviews)
   - Time required to visit
   - Entrance fee
   - Airport accessibility
5. Destinations are ranked based on the final score

---

## 🧮 Scoring Formula
Final Score =
(0.35 × Google Rating) +
(0.35 × Popularity) +
(0.15 × Time Score) +
(0.10 × Cost Score) +
(0.05 × Airport Accessibility Score)

yaml
Copy code

Higher score ⇒ Better weekend destination.

---

## 📊 Sample Output
The system displays:
- Destination name
- City
- Time required
- Rating
- Entrance fee
- Popularity
- Airport availability
- Best time to visit
- Final score

---

## 🗂️ Project Structure
weekend-destination-project/
│── dataset/
│ └── Top Indian Places to Visit.csv
│── notebook.ipynb
│── output_images/
│ ├── output1.png
│ ├── output2.png
│ └── output3.png
│── README.md

yaml
Copy code

---

## ▶️ How to Run the Project
1. Open **Google Colab**
2. Upload the dataset CSV file
3. Run the notebook cells
4. Enter a source city when prompted
5. View ranked weekend destinations

---

## 📌 Applications
- Travel recommendation systems
- Tourism analytics
- Weekend trip planning
- Academic data science projects

---

## 🚀 Future Enhancements
- Add machine learning-based recommendations
- Include seasonal filtering
- Use real-time APIs for dynamic data
- Add visual dashboards

---

## 🧑‍💻 Author
**Your Name**  
B.Tech / BCA / MCA  
Department of Computer Science

---

## 📜 License
This project is for **educational purposes only**.