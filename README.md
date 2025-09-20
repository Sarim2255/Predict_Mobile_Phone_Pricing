## 📱 Mobile Price Range Prediction

### 🔍 Project Overview
This project uses machine learning to predict the price range of mobile phones based on their specifications. The goal is to classify phones into four categories: **Low**, **Medium**, **High**, and **Very High** price range.

### 📊 Dataset
- The dataset includes features like:
  - `battery_power`
  - `ram`
  - `fc`
  - `pc`
  - `px_height`
  - `px_width`
  - `talk_time`
  - `n_cores`
  - `pc`
  - `px_height`
  - `px_width`
  - `ram`
  - `sc_h`
  - `sc_w`
  - `talk_time`
  - `three_g`
  - `touch_screen`
  - `wifi`
- Target variable: `price_range` (0: Low, 1: Medium, 2: High, 3: Very High)

### 🧪 Workflow
1. **Data Loading & Exploration**
2. **EDA (Exploratory Data Analysis)**
3. **Feature Engineering**
4. **Model Building**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - K-Nearest Neighbors
5. **Model Evaluation**
6. **Prediction on Sample Data**

### 🧠 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

### 📈 Results
- Random Forest achieved the highest accuracy.
- RAM and battery power were the most influential features.

### 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/Sarim2255/Predict_Mobile_Phone_Pricing.git
   ```
2. Open the notebook in Google Colab or Jupyter.
3. Run cells sequentially and upload the dataset when prompted.
