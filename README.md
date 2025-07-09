# Mall Customer Segmentation using KMeans & PCA

This project uses unsupervised machine learning techniques to segment mall customers based on their annual income, spending score, and demographics. It helps businesses personalize marketing strategies.

## 🚀 Technologies Used
- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- KMeans Clustering
- PCA (Principal Component Analysis)

## 📊 Dataset
- **Mall_Customers.csv**  
  Contains customer info: Age, Gender, Annual Income, Spending Score.

## 📌 Key Steps
- Cleaned and preprocessed data (mapped Gender, dropped ID)
- Scaled features with StandardScaler
- Determined optimal clusters using Elbow Method
- Trained `KMeans` model to assign clusters
- Reduced dimensions using PCA for 2D visualization
- Visualized clusters using scatter plots and boxplots
- Exported final segmented data to CSV

## 📈 Output
- **Visuals** of clusters
- **Final CSV** with cluster and PCA data
- Business-friendly customer segmentation

## 🗂️ Files
- `mall_segmentation_project.ipynb` → Code Notebook
- `Final_Mall_Customer_Segments.csv` → Final result
- `requirements.txt` → List of dependencies

## 🤝 Author
- Built by [Your Name](https://github.com/yourusername)
