# 📊 Data Curation Techniques  

## 📖 Overview  
This repository contains various **data curation techniques** used for preparing and cleaning data before analysis. Data curation ensures the quality, consistency, and usability of datasets.  

## 🔍 Topics Covered  

1. **Web Scraping** - Extracting data from websites using Python libraries like BeautifulSoup and Scrapy.  
2. **Summary Statistics** - Generating insights using measures like mean, median, variance, and standard deviation.  
3. **Handling Missing Values** - Techniques to deal with missing data using imputation and deletion methods.  
4. **Handling Outliers** - Detecting and treating outliers using statistical methods like IQR, Z-score, and transformations.  
5. **Normalization** - Scaling data using techniques like Min-Max normalization and Z-score standardization.  
6. **Chi-Square Test** - Performing chi-square tests for independence and goodness of fit in categorical data analysis.  
7. **K-Nearest Neighbors** - Classification using the KNN algorithm with and without data normalization.
8. **Outlier** - Finding outlier using different techniques like Z-score , IQR , Binning . 
9. **PCA** -  Principal Component Analysis (PCA) is used for reducing the dimensionality of large datasets while preserving as much variability (information) as possible
10. **Pearson** -  Pearson correlation is a statistical measure used in data curation to quantify the linear relationship between two numerical variables
11. **Sampling** -  Using mulitiple sampling techniques for data numerosity reduction and also solving imbalaced dataset


## 📝 Example Notebooks

### K-Nearest Neighbors (KNN) Example
The [`k-nn_example.ipynb`](./Data%20Curation/k-nn_example.ipynb) notebook demonstrates:
- Implementation of the KNN classification algorithm using scikit-learn
- Comparison between normalized and non-normalized data processing
- A practical example of teen/adult classification based on height and age features
- How feature scaling affects KNN classification results

Key concepts illustrated:
- Distance-based classification
- The importance of feature normalization when attributes have different scales
- Impact of the k value (number of neighbors) on classification results

## ⚙️ Installation & Usage  

1. **Clone the repository**  
   ```sh
   git clone https://github.com/Tech-Abhang/Data-Curation.git
   cd Data-Curation
   ```

2. **Install required packages**
   ```sh
   pip install numpy pandas matplotlib scikit-learn scipy seaborn statsmodels beautifulsoup4
   ```

3. **Open the notebooks**
   ```sh
   jupyter notebook
   ```
   Navigate to the specific technique folder to access the example notebooks.

## 🛠️ Technologies Used
- Python 🐍
- Pandas 📊
- NumPy 🔢
- BeautifulSoup 🌐
- Scipy & Statsmodels 📈
- Matplotlib & Seaborn 📉
- Scikit-learn 🤖

## 📚 Additional Resources
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [K-Nearest Neighbors Algorithm](https://scikit-learn.org/stable/modules/neighbors.html)
- [Data Normalization Techniques](https://scikit-learn.org/stable/modules/preprocessing.html)

## 📋 License
This project is available for educational purposes. Please check individual source files for specific licensing information.

## 👤 Author
- [Abhang Sudhir Pawar](https://github.com/Tech-Abhang)