# Netflix-Recommendation-Engine-PROJECT
# Netflix Recommendation Engine 🎬

This project builds a movie recommendation system using the **Singular Value Decomposition (SVD)** algorithm. It predicts user ratings for movies they haven't watched yet, based on past ratings—similar to how Netflix recommends movies.

---

## Tech Stack & Tools
- **Python**
- **Pandas**, **NumPy**
- **Surprise** Library (for building recommendation systems)


## Objective
To develop a collaborative filtering recommendation engine that:
- Understands user preferences through historical ratings
- Suggests movies likely to be enjoyed
- Evaluates performance using **Root Mean Square Error (RMSE)**


## Methodology
1. **Data Preprocessing** using Pandas
2. **Model Building** using SVD from the Surprise library
3. **Evaluation** with `cross_validate()` to measure RMSE


