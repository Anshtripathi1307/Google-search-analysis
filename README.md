# 🌍 Google Search Trend Analysis

## 📘 Overview
This project analyzes **Google search trends** for any keyword using the **Pytrends API**.  
It helps you visualize how interest in a particular topic changes over time, which countries search it the most, and related search terms.  
With just one keyword input, you can generate **interactive graphs**, **world maps**, and **trend comparisons** in minutes.

---

## 🎯 Objectives
The notebook covers the following tasks:

1. **Automated Keyword Search** – Easily analyze any keyword by changing one variable.  
2. **Top 15 Countries Analysis** – Identify where the keyword is most searched.  
3. **Global Visualization** – Display a **world map** highlighting countries with high interest.  
4. **Time-based Trend Analysis** – Explore how keyword popularity evolved over time.  
5. **Keyword Comparison** – Compare multiple related keywords using visual graphs.

---

## 🧠 Features
- 🔍 Fetches real-time search data using **Google Trends API**  
- 📊 Interactive visualizations with **Plotly Express**  
- 🌐 Global heatmaps showing keyword interest by country  
- 📈 Trend charts and comparisons between related keywords  
- 📅 Time-series analysis to understand topic popularity over years  

---

## 🛠️ Technologies Used
| Category | Libraries / Tools |
|-----------|-------------------|
| Data Collection | `pytrends` |
| Data Analysis | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn`, `plotly.express` |
| Environment | Jupyter Notebook (.ipynb) |

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/google-search-analysis.git
cd google-search-analysis
pip install -r requirements.txt
```

Or install libraries manually:
```bash
pip install pytrends plotly pandas matplotlib seaborn
```

---

## 🚀 Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook 03_google\ search\ analysis.ipynb
   ```
2. Change the keyword in the code:
   ```python
   keyword = "Machine learning"
   ```
   (You can replace it with any keyword, e.g., `"AI"`, `"Cricket"`, `"Bitcoin"`)

3. Run all cells to generate:
   - Top 15 countries bar chart  
   - World heatmap (interactive)  
   - Time-series trend graph  
   - Keyword comparison chart  

---

## 📊 Sample Outputs
- **Top Countries Visualization**
  - Displays the 15 countries where the keyword is searched most.
- **World Map**
  - Interactive map using Plotly showing search intensity.
- **Time-Series Graph**
  - Interest over time for the keyword.
- **Comparison Plot**
  - Compare interest between related keywords.

---

## 🧩 Example Keywords
- `"Machine learning"`  
- `"Artificial intelligence"`  
- `"Data Science"`  
- `"Python programming"`  

---

## 📈 Future Enhancements
- Automate multiple keyword comparisons.  
- Integrate dashboard using **Streamlit** or **Dash**.  
- Add trend forecasting using **Prophet**.

---

## 📄 Author
**Ansh Tripathi**  
UI/UX Designer & Data Enthusiast  
📧 [your-email@example.com]  
📸 [Instagram](https://instagram.com/) • 🧑‍💻 [GitHub](https://github.com/yourusername)

---

## 🪪 License
This project is licensed under the **MIT License** – feel free to use and modify it.
