Inflation Rate Prediction Using Time Series Deep Learning

This project aims to develop an interactive forecasting system for the Inflation Rate using a Time Series Deep Learning model. The user interface (GUI) is built using Streamlit to facilitate the visualization of historical data and perform predictions in real-time.Key FeaturesTime Series Forecasting: Uses a Deep Learning model (including pre-trained models like N-BEATS) implemented with Keras/TensorFlow to predict future inflation rates.Interactive User Interface (GUI): Provides a web-based interface developed with Streamlit for easy interaction, data visualization, and viewing prediction results.Pre-trained Models: Includes pre-trained Deep Learning model files (.h5) so users can immediately run the prediction application without needing to retrain the model.Historical Data: Works with historical time series data of inflation rates (a .csv file) as input for the model.Technology UsedCategoryTechnologyDescriptionMachine LearningTensorFlow & KerasThe main Deep Learning framework used to build and load time series models.GUI & WebStreamlitPython library for rapid creation of web-based user interfaces.ProgrammingPythonThe main programming language used for the entire project.Data SciencePandas & NumPyUsed for manipulation, processing, and analysis of time series data.Installation PrerequisitesEnsure you have Python 3.x installed. Then, install all necessary dependencies using the requirements.txt file:Bash# 1. Clone the repository
git clone <YOUR_REPO_URL>
cd <REPO_FOLDER_NAME>

# 2. Create and activate a virtual environment (Optional, but recommended)
python -m venv venv
source venv/bin/activate  # For Linux/macOS
# venv\Scripts\activate   # For Windows

# 3. Install all required libraries
pip install -r requirements.txt
The main libraries installed include streamlit, tensorflow, keras, pandas, and numpy.Project Structure.
├── GUI.py                               # Main Streamlit script for the user interface.
├── requirements.txt                     # List of all Python dependencies.
├── final_model_fix2.h5                  # Pre-trained Deep Learning model file.
├── model_nbeats.h5                      # Alternative pre-trained Deep Learning model file.
└── inflation.xlsx - Sheet1.csv          # Historical dataset used for training and prediction.
Example UsageAfter installing all prerequisites, you can run the Streamlit web application directly from your terminal.Ensure you are in the project's root directory.Run the Streamlit application:Bashstreamlit run GUI.py
Access the Application:Your web browser will automatically open and navigate to the prediction application (usually at http://localhost:8501).In the Streamlit interface, you can interact with the historical data visualization and view the inflation rate prediction results.
