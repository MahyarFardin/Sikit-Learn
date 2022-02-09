# Overviwe

In this project I tried to cluster the fastfood restourants.

# Walkthrough

  First I imported libraries which are needed for basic feature engineering and data-visualization
and dataset itself, then I extracted information about the general affairs of dataset to see the data type
of each column and to find the missing values. I removed some columns which had a lot of unique values and droped the nan values.
The I get the pca to see that whethe I can visually cluester datas or not, I confronted some missing values and I removed them(I could also
not dropt them because some models can handel missing values but in order to make sure i removed them). Then I saw clear 5 clusters find the best cluster number 
and I started to apply my models. 

  **BEFORE PCA**
  
![](https://github.com/MahyarFardin/Sikit-Learn/blob/main/Unsupervised-Learning/American_Fastfood_Clustering/results/1.jpg)

  **AFTER PCA**
  
![](https://github.com/MahyarFardin/Sikit-Learn/blob/main/Unsupervised-Learning/American_Fastfood_Clustering/results/2.jpg)

  **ELBOW**
![](https://github.com/MahyarFardin/Sikit-Learn/blob/main/Unsupervised-Learning/American_Fastfood_Clustering/results/3.jpg)  

# Results
<ol>
  <li>DBSCAN &amp; SpectralClustering</li>
  <li>Gaussian mixture</li>
  <li>AgglomerativeClustering</li>
  <li>Optic</li>
  <li>Kmeans</li>
</ol>
  

# Feedback

If you have any feedback, please reach out to us at Mahyarfardinfar@gmail.com
