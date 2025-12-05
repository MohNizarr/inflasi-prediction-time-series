# Inflation Rate Prediction Using Time Series Deep Learning

![Time Series](time series.jpeg)

This project aims to develop an interactive forecasting system for the **Inflation Rate** using a **Time Series Deep Learning** model. The user interface (GUI) is built using **Streamlit** to facilitate the visualization of historical data and perform predictions in real-time.

[Image of a time series prediction graph showing historical data and future forecast]

-----

## Key Features

  * **Time Series Forecasting:** Uses Deep Learning models (like N-BEATS) implemented with Keras/TensorFlow to predict future inflation rates.
  * **Interactive User Interface (GUI):** Provides a user-friendly, web-based interface built with Streamlit for visualization and prediction.
  * **Pre-trained Models:** Includes pre-trained model files (`.h5`) for immediate use, eliminating the need for initial training.
  * **Historical Data:** Utilizes historical inflation rate data (provided in the `.csv` format) for analysis and prediction.

-----

## Technology Used

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Machine Learning** | TensorFlow & Keras | The core Deep Learning framework used for model implementation. |
| **GUI & Web** | Streamlit | Python library for creating the interactive web application. |
| **Programming** | Python | The primary language used. |
| **Data Science** | Pandas & NumPy | Used for data handling, preprocessing, and numerical operations. |

-----

## Installation Prerequisites

Ensure you have **Python 3.x** installed. Then, install all necessary dependencies using the provided `requirements.txt` file.

```bash
# 1. Clone the repository
git clone <YOUR_REPO_URL>
cd <REPO_FOLDER_NAME>

# 2. Create and activate a virtual environment (Recommended)
python -m venv venv
source venv/bin/activate  # For Linux/macOS
# venv\Scripts\activate   # For Windows

# 3. Install all required libraries
pip install -r requirements.txt
```

The installation will include `streamlit`, `tensorflow`, `keras`, `pandas`, and `numpy`.

-----

## Project Structure

```
.
├── GUI.py                               # Main Streamlit script for the user interface.
├── requirements.txt                     # List of all Python dependencies.
├── final_model_fix2.h5                  # Primary pre-trained Deep Learning model file.
├── model_nbeats.h5                      # Alternative pre-trained Deep Learning model file.
└── inflation.xlsx - Sheet1.csv          # Historical dataset used for prediction.
```

-----

## Example Usage

Once the prerequisites are installed, run the Streamlit web application from your terminal.

1.  **Ensure you are in the project's root directory.**

2.  **Run the Streamlit application:**

    ```bash
    streamlit run GUI.py
    ```

3.  **Access the Application:** Your web browser will automatically open and navigate to the application (usually at `http://localhost:8501`). You can then interact with the visualizations and view the predicted inflation rates.

-----

