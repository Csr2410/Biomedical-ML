#1.Set Up Your Environment
Open the project folder in Visual Studio Code.
Make sure you have the Jupyter extension installed for running notebook cells.

#2. Data Loading and Feature Extraction
Run the first cell in the notebook to load the Google Speech Commands dataset.
This step extracts essential audio features like MFCC, Chroma, Spectral Contrast, RMSE, and ZCR.
The processed data will be saved as features.csv 

#3. Train-Test Split
The dataset is split into training (80%) and testing (20%) subsets using stratified sampling.
The training set is saved as train_data.csv, and the test set is saved as test_data.csv.

#4. Train the SVM Model, Random Forest, Decision Tree
Train the Support Vector Machine (SVM) classifier, Random Forest, Decision Tree
Use cross-validation and hyperparameter tuning to optimize the models.

#5.Evaluate the models using metrics such as accuracy, precision, recall, and F1 score.
Generate and analyze the confusion matrix to visualize class-level performance.

#6.Perform Statistical Analysis
Conduct ANOVA tests to analyze the significance of cross-validation scores across models.
Perform Kruskal-Wallis tests to assess feature significance or compare model performances.
Use these tests to validate if performance differences are statistically significant.

#7.Save all results, including metrics, plots, and confusion matrices, for documentation.
Make sure to organize outputs into appropriate folders for easy reference.