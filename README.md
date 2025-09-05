# ED22B054_Assignment2
PCA on mushroom Dataset
This project applies Principal Component Analysis (PCA) to the Mushroom dataset to study how dimensionality reduction can help in understanding and classifying mushrooms as edible or poisonous.

Goals
The aim of this assignment is to connect concepts from linear algebra, feature spaces, and dimensionality reduction with a real-world classification problem. Specifically, it focuses on:
	•	Using PCA to convert high-dimensional, one-hot encoded categorical data into a smaller set of independent components.
	•	Tackling multicollinearity that occurs due to categorical encoding.
	•	Demonstrating how reducing dimensions speeds up training and cuts down on computational resources.
	•	Comparing model results with Logistic Regression before and after PCA transformation.
	•	Visualizing mushrooms in the reduced PCA space to see how well the two classes separate.

Why PCA Helps
	•	Removes correlation: Converts related features into independent principal components.
	•	Improves efficiency: Fewer dimensions mean faster learning and less chance of overfitting.
	•	Aids visualization: Projecting onto the first 2–3 components provides a clear picture of class grouping.

Visualization Approach
We generate pairwise plots of the leading principal components to check how well edible and poisonous mushrooms cluster apart.

Key Insights
	•	Explained Variance: About 95% of the data’s variation is retained within the first 59 components, making them a solid choice for reduction while keeping the dataset’s information intact.
	•	Scatter Plots (PC1 vs PC2): The two classes show strong separation with minimal overlap, proving PCA’s usefulness in uncovering structure in the dataset.
	•	Logistic Regression Results with PCA:
	•	Accuracy: ~99.9%, almost identical to the original model.
	•	Precision, Recall, and F1-score: ≈ 1.0 for both edible and poisonous categories.
	•	Errors: Extremely few, meaning PCA preserved the important information needed for classification.

