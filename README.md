# ML Health Insurance Premium Prediction

Health Insurance Premium Prediction is a predictive model to estimate health insurance premiums based on factors like age, smoking habits, BMI, and medical history. The objective of this project is :
- Developed a high-accuracy (>97%) premium prediction model by using model segmentation approach.
- Create an interactive Streamlit application that an underwriter can use for predictions and deploy it on Streamlit Cloud.

## Techstack
- **Python**
- **Streamlit for frontend development**
- **XGBoost and Linear Regression Algorithmns for Model training**


## Project Structure

- **main.py and prediction_helper.py**: Contains Streamlit and model prediction code.
- **notebooks and artifacts folder**: Contains all the jupyter notebook and required data. 
- **requirements.txt**: Lists the required Python packages.
- **artifact folder**: Contains the exported model as joblib file


## Setup Instructions

1. **Clone the repository**:
   ```bash
     git clone https://github.com/Himanshu-b20/ML-Health-Premium-Prediction.git
   ```
2. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
3. **Run the Streamlit app:**:   
   ```commandline
    streamlit run /main.py

## Streamlit UI

<img width="1728" height="1121" alt="image" src="https://github.com/user-attachments/assets/4c0da0b7-dcc7-4c00-b58b-4970cfcb6e10" />

   ```
