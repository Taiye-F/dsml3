Project Title: 
Unsupervised Learning on Real-World Countries' Health Data

Overview: 
This project uses K-Means clustering to group 167 real-world countries based on key health indicators such as child mortality, life expectancy, and health expenditure. The goal is to identify natural groupings, such as developed and developing nations, based on their health profiles.

Dataset: 
•	Source: Kaggle - Unsupervised Learning on Country Data

•	Features include: 
    o	child_mortality: Number of deaths per 1000 live births
    o	life_expectancy: Average lifespan in years
    o	health: Health expenditure per capita
    o	income, inflation, GDP, and more

Methodology: 
  1.	Data Preprocessing
    o	Selected relevant health indicators
    o	Scaled features using StandardScaler

  2.	Clustering
    o	Applied K-Means with 2 clusters to distinguish between developed and developing countries
    o	Used the Elbow Method to validate cluster count
  
  3.	Labelling
    o	Cluster 0 → Developing
    o	Cluster 1 → Developed

Cluster Summary: 
Cluster 0 (Developing): Higher child mortality, lower life expectancy, and lower health expenditure per capita
Cluster 1 (Developed): Lower child mortality, higher life expectancy, and higher health expenditure per capita

Contributions:
Pull requests are welcome! Feel free to suggest improvements or new visualizations.
