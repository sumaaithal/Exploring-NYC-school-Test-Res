### Exploring-NYC-school-Test-Results


Every year, high school students across the U.S. take the SAT — a standardized test assessing literacy, numeracy, and writing proficiency. With each section (Reading, Math, Writing) scored out of 800, SAT scores play a vital role in shaping students’ college admission prospects.

This project analyzes SAT performance across New York City (NYC) public high schools to uncover meaningful patterns that can guide decision-making for policymakers, researchers, and parents.

---

## 📁 Dataset Overview

The dataset `schools.csv` contains SAT performance data for NYC public high schools. Each row represents one school, along with its location and average SAT scores.

| Column Name       | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `school_name`     | Name of the public high school                                              |
| `borough`         | One of NYC’s five boroughs (e.g., Bronx, Manhattan, Brooklyn, etc.)         |
| `building_code`   | Unique code identifying the school building                                 |
| `average_math`    | Average Math SAT score (out of 800)                                         |
| `average_reading` | Average Reading SAT score (out of 800)                                      |
| `average_writing` | Average Writing SAT score (out of 800)                                      |
| `percent_tested`  | Percentage of students at the school who took the SAT                       |

---

## ❓ Questions Explored

1. **Which NYC schools have the best math results?**  
   Identified top schools based on average Math SAT scores.

2. **What are the top 10 performing schools based on the combined SAT scores?**  
   Calculated total score by summing the average scores from Math, Reading, and Writing sections.

3. **Which single borough has the largest standard deviation in the combined SAT score?**  
   Measured borough-wise variability to determine disparities in school performance.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📌 Key Insights

- Schools with high math scores don't always rank highest overall — balanced performance matters.
- The top-performing schools are geographically diverse.
- One borough shows significantly more variation in SAT performance, indicating possible inequality in educational quality.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nyc-sat-analysis.git

2. Open analysis.ipynb in Jupyter Notebook or JupyterLab.
3. Run all cells to view the analysis and visualizations.

---
#### For questions, feedback, or collaboration, feel free to reach out via LinkedIn or open an issue on this repository

