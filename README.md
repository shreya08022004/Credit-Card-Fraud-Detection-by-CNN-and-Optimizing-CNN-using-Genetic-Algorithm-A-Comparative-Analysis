# Abstract
Credit Card Fraudulent Transaction detection plays a crucial role in the financial industry, where the rise in fraudulent activities necessitates systems that can detect these transactions. The proposed work aims to explore the effectiveness of Genetic Algorithms (GAs) and compare its performance with traditional machine learning algorithms in optimizing fraudulent transaction detection, enhancing both accuracy and efficiency. The main objective is to develop credit card fraudulent transaction detection systems using XGBoost Classifier, Isolation Forest, Convolutional Neural Network (CNN) and optimizing CNN using Genetic Algorithm and to evaluate the effectiveness of GA compared to other models. It also aims at showing the importance of balanced dataset for fraud detection. The novelty of the work lies in the integration of Genetic Algorithm, offering an optimized approach over traditional methods, as well as conducting a comparative analysis to highlight the advantages of GA. The proposed work aims to show how GA can improve system robustness and adaptability, ultimately enhancing accuracy. The proposed work observed that the GA optimized CNN trained on a balanced dataset has the highest accuracy and low false positives.

# Procedure
- First two datasets are generated. The first one is the imbalanced (original) dataset and the second is a balanced dataset generated using the technique of SMOTE during the execution of the program.
- The models are built and trained on the datasets.
- The CNN model is optimized using Genetic Algorithm.
- The Genetic Algorithm is an optimization algorithm, and in this project, it is used for tuning hyperparameters of the CNN.
- The Genetic Algorithm gives the best hyperparameter set after the continuous process. The GA runs in a loop.
- The GA consists of the following steps in a loop:
    - Population Initialization
    - Fitness Evaluation
    - Selection
    - Crossover
    - Mutation

# How to Execute
- Download the dataset
- Upload your dataset in the drive
- Connect the Google Colab to your drive
- Run the above programs in Google Colab

# Note
The Genetic Algorithm model works well and faster using GPU.

# How to Change the Runtime Environment to GPU
Go to **Runtime** ---> Click on **Change Runtime** ---> Select the **T4 GPU** option ---> Save the changes
