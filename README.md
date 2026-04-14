# FWI Prediction App

This is a Flask-based web application that predicts the Fire Weather Index (FWI) using a machine learning model.

## Features
- Predicts FWI based on Temperature, RH, Ws, Rain, FFMC, DMC, ISI, Classes, and Region.
- Simple web interface using HTML.
- Uses a Ridge Regression model(because it give 97% accuracy for this model training).

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd 3.0-Model+Training
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv .venv
   ```

3. **Activate the virtual environment:**
   - **Windows:**
     ```bash
     .\.venv\Scripts\activate
     ```
   - **Mac/Linux:**
     ```bash
     source .venv/bin/activate
     ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the application:**
   ```bash
   python application.py
   ```

6. **Access the app:**
   Open your browser and go to `http://127.0.0.1:5000/`.

## Deployment
For hosting on platforms like **Render** or **Heroku**:
- Ensure all dependencies from `requirements.txt` are installed.