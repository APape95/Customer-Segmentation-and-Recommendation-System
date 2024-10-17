# 🎯 Customer Segmentation Using Machine Learning

This data science project focuses on segmenting customers based on their purchasing behavior using unsupervised machine learning techniques. By analyzing customer demographics and spending patterns, I have grouped customers into distinct segments, providing valuable insights that can inform business strategies such as targeted marketing and personalized services.

## 📊 Project Overview
In this project, I analyzed customer purchasing behavior using clustering algorithms to identify distinct customer segments. The results of this segmentation can help businesses better understand their customer base and make data-driven decisions to improve customer satisfaction and optimize marketing efforts. The insights are visualized using an interactive Tableau dashboard, which stakeholders can explore to gain a deeper understanding of their customer groups.

You can explore the **interactive dashboard** on Tableau [here](https://public.tableau.com/app/profile/amy.pape/viz/CustomerSegmentationInsightsDashboard/CustomerSegmentationInsightsDashboard?publish=yes).

### 🎯 Objective
The main goal of this project is to segment customers based on their purchasing habits and demographic data. By identifying these distinct customer groups, businesses can gain insights into customer behavior and use this information to optimize marketing strategies, improve customer engagement, and enhance product offerings.

## 💡 Skills Demonstrated

- **🧼 Data Cleaning & Preprocessing**: I used `pandas` and `NumPy` to clean and transform the dataset, handling missing data and outliers to prepare the data for analysis.
  
- **📈 Clustering Algorithms**: I applied unsupervised learning techniques, including **K-means clustering**, to group customers into meaningful segments based on their purchasing behavior and demographic information.

- **🔮 Dimensionality Reduction**: I employed **Principal Component Analysis (PCA)** to reduce the dimensionality of the data, enabling easier visualization of customer segments.

- **📊 Data Visualization**: I created visualizations using `Matplotlib` to explore the clusters and relationships between customer features. Additionally, I developed an interactive dashboard using **Tableau** to allow stakeholders to explore the results dynamically.

- **📊 Dashboard Creation**: I exported the segmented customer data into a CSV file and visualized the results in **Tableau**, providing an easy-to-navigate platform for further exploration of customer segments.

## 🛠️ Tools & Technologies

- **🐍 Python**: The main programming language I used for data analysis, clustering, and visualization.
- **🗂️ Pandas & NumPy**: Libraries used extensively for data manipulation, cleaning, and preprocessing.
- **📦 Scikit-learn**: I used this library for implementing clustering algorithms and dimensionality reduction techniques.
- **📊 Matplotlib**: I utilized this for generating data visualizations during exploratory analysis.
- **📊 Tableau**: I created an interactive dashboard to visualize the customer segments and insights, allowing non-technical stakeholders to explore the data. You can view the dashboard [here](https://public.tableau.com/app/profile/amy.pape/viz/CustomerSegmentationInsightsDashboard/CustomerSegmentationInsightsDashboard?publish=yes).
- **📓 Jupyter Notebook**: I documented the project and performed all analysis in an interactive environment.

## 📁 Dataset
The dataset used for this project is the [Mall Customer Segmentation Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation) from Kaggle, which includes customer demographic data and purchasing behavior. Key features of the dataset include:

- **🆔 Customer ID**
- **👤 Age**
- **💵 Annual Income**
- **📊 Spending Score** (based on customer purchasing habits)

## 🛠️ Project Workflow

### 1. 🧼 Data Preprocessing
- I loaded the dataset using `pandas`, conducted exploratory data analysis, and handled missing values and outliers.
- The data was scaled to ensure that clustering algorithms, which are sensitive to the scale of input features, performed optimally.

### 2. 📈 Clustering
- I applied **K-means clustering** to segment the customers based on key features such as age, income, and spending score.
- To visualize the clusters, I used **Principal Component Analysis (PCA)** to reduce the dimensionality of the data, making it easier to display the customer groups in 2D space.

### 3. 📊 Visualizations & Insights
- I generated various visualizations, such as scatter plots and boxplots, to explore the relationships between features like age, income, and spending behavior within each cluster.
- I created an interactive **Tableau** dashboard to allow stakeholders to explore these customer segments and insights dynamically. You can view the dashboard [here](https://public.tableau.com/app/profile/amy.pape/viz/CustomerSegmentationInsightsDashboard/CustomerSegmentationInsightsDashboard?publish=yes).

### 4. 🔍 Insights & Business Strategy
- I identified several distinct customer segments, including high-income frequent buyers, younger moderate spenders, and budget-conscious older customers.
- These segments provide valuable insights into how businesses can tailor their marketing strategies for each group, enhancing customer engagement and improving sales efficiency.

## 📈 Key Results

- **🧑‍🤝‍🧑 Identified Customer Segments**: I successfully segmented customers into distinct groups based on their purchasing behavior and demographic features.
- **📊 Data Export for Dashboards**: I exported the segmented data to a CSV file, which was then used to create an interactive dashboard in **Tableau**. This dashboard allows stakeholders to explore the customer segments and gain actionable insights.
- **📊 Interactive Dashboard**: The interactive **Tableau** dashboard provides a user-friendly way to visualize the customer segments and insights, making it easy for business users to explore the results. Check out the dashboard [here](https://public.tableau.com/app/profile/amy.pape/viz/CustomerSegmentationInsightsDashboard/CustomerSegmentationInsightsDashboard?publish=yes).

## 🚀 Conclusion
This project showcases my expertise in **data preprocessing**, **unsupervised machine learning**, and **data visualization**. By using customer segmentation, businesses can better understand their customer base and develop more targeted marketing strategies. The insights gained from this analysis can lead to more effective engagement and increased revenue potential.

## 🛠️ Technologies & Frameworks
- **💻 Programming Language**: Python
- **📦 Libraries**: pandas, NumPy, scikit-learn, Matplotlib
- **📊 Visualization Tools**: Matplotlib, Tableau
- **📝 IDE**: Jupyter Notebook

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

