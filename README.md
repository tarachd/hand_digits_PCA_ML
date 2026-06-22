# hand_digits_PCA_ML
Goal:
hand digits - dimensionality reduction using principal component analysis and digits classification

This dataset contains handwritten digits from 0 to 9. Each image is very small, only 8×8 pixels, but that still gives us 64 numeric features per image. Since we cannot visualize 64 dimensions, I used Principal Component Analysis, or PCA, to reduce those 64 features into 3 main components: PCA1, PCA2, and PCA3.


These components are not original pixels. Instead, they are new features created by combining the original pixel values in a way that captures the largest patterns in the data. So this 3D plot gives us a simplified view of the dataset while still preserving important structure.


In the 3D plot, each point represents one handwritten digit image. Points that are close together have similar pixel patterns, while points that are far apart look more different. The colors represent the actual digit labels from 0 to 9.



The purpose of this 3D plot is not to get the highest prediction accuracy. It is mainly for understanding and visualizing the data. 
For classification, I later used Logistic Regression and compared full 64-feature data with PCA-reduced data.