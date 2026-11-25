# NextWage

An interactive Machine Learning web application that predicts employee salaries based on factors such as age, education level, number of skills, current salary and years of experience. The project uses the selected model to generate salary predictions.

The application follows an end-to-end ML workflow including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and deployment using Streamlit.


# Tech Stack

Python • Pandas • NumPy • Scikit-learn • Matplotlib • Streamlit


## 📊 Model Performance

| Model | R² Score | RMSE |
| :--- | ---: | ---: |
| Linear Regression | **98.01%** | **0.034083** |
| Random Forest Regressor | **97.37%** | **0.039152** |
| Decision Tree Regressor | **94.32%** | **0.047217** |


🚀 Live Demo

"Streamlit App": https://nextwage-k5nkrdydqug6m55pjexabe.streamlit.app/

## Prerequisites

- **Python 3.8+** installed on your system
- **Git** (optional, required only if cloning via terminal)

## Getting Started

### 1. Download or Clone the Repository

**Option A: Clone via Git**
```bash
git clone [https://github.com/grananyarao/NextWage.git](https://github.com/grananyarao/NextWage.git)
cd NextWage
```

**Option B: Download ZIP**
1. Click the green **Code** button at the top right of this repository page.
2. Select **Download ZIP**.
3. Extract the downloaded archive to a folder on your computer.
4. Open a terminal or command prompt inside the extracted `NextWage` folder.

### 2. Set Up a Virtual Environment (Recommended)

Creating a virtual environment keeps project dependencies isolated from your global Python installation.

**Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

Install all required Python packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Run the Application

Start the local server using the main entry point script:

```bash
streamlit run app.py
```

Once running, the app should open automatically in your default browser. If it does not, navigate to `http://localhost:8501`.

*(Note: Replace `app.py` with your main filename if it is named differently, or run `python app.py` if it is not a Streamlit app.)*
