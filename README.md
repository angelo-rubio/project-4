# Project 4: Supervised learning - Classifications (Logistic regression and Decision Tree)

## Overview
This project applies classification techniques (e.g., Logistic Regression and Decision Trees) to predict the likelihood of hotel booking cancellations. By identifying factors like lead time, room pricing, special requests, and market segments, the project offers actionable insights into reducing hotel reservation cancellations. Pre and post prunning techniques are used to optimize the decision tree model.

## Project Structure
- **Project 4 Angelo Rubio.ipynb**  
  Jupyter Notebook with data exploration, model building, and machine learning workflow.
- **Hotel Booking Dataset**  
  Dataset containing reservation details, cancellations, and relevant features.
- **README.md**  
  Documentation, installation guides, and usage instructions.

## Getting Started
1. **Install dependencies**  
- Python 3.x
- Pandas
- Numpy
- scikit-learn
- matplotlib
- seaborn

2. **Set up environment**
```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

3. **Run the Notebook**
- Restart the kernel and run cells in sequence.

## Methodology
1. **Data Loading** : Loads and cleans hotel reservation data.
2. **Exploratory Analysis** : Investigates relationships among lead time, room type, special requests, etc.
3. **Preprocessing** : Encodes features and splits data into training/testing sets.
4. **Modeling** : Builds classification models (e.g., Logistic Regression) to predict cancellation.
5. **Evaluation** : Uses metrics like accuracy, precision, recall, and the confusion matrix to gauge model performance.
6. **Results & Insights** :
- Lead Time: Longer lead times often increase the likelihood of cancellation.
- Special Requests: More special requests correlate with fewer cancellations.
- Market Segment: Online reservations show higher cancellation rates compared to offline channels.
