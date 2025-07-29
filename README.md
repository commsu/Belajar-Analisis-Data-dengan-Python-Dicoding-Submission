# 🚴‍♂️ Bike Sharing Analysis Dashboard

![This Dashboard project is rated 5 stars](https://raw.githubusercontent.com/commsu/Belajar-Analisis-Data-dengan-Python-Dicoding-Submission/master/penilaian-submission/Screenshot%202025-01-12%20162323.png)

## 🛠️ Tools and Libraries
The project uses the following libraries (as listed in the `requirements.txt` file):
- **Streamlit**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Plotly**
- **Folium**
- **GeoPandas**

## 🌐 Live Demo
After deploying the dashboard, retrieve the public URL by running:
```bash
cat url.txt
```
Open the displayed URL in your browser to explore the live dashboard.

### 1. Setup env using anaconda
```bash
# create new env
conda create -n bike_dashboard_env python=3.8
conda activate bike_dashboard_env
# Install requirements
pip install -r requirements.txt
```

### 2. Setup env using Terminal/Shell
```bash
# Install requirements directly
pip install -r requirements.txt
```

### 3. Setup env using Pipenv
```bash
# Install pipenv if not already installed
pip install pipenv
# Create and enter virtual environment
pipenv install
pipenv shell
pipenv install -r requirements.txt
```

### Run the dashboard
```bash
cd dashboard
streamlit run dashboard.py
```
