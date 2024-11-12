# Glaucoma-Detection-using-Clinical-Notes-
This project aims to classify glaucoma presence based on patient clinical notes using machine learning and deep learning techniques. By leveraging natural language processing (NLP) on electronic health record (EHR) data, this project strives to develop a robust model that can aid healthcare professionals in early detection of glaucoma, which is crucial for timely intervention and treatment.

# Key Features

  1. Data Preparation and Preprocessing:
     The dataset contains clinical notes along with relevant patient details, such as age, gender, ethnicity, and language. These features are used to provide context for the glaucoma classification model.
  2. Deep Learning Model:
     Utilizes both LSTM and CNN-based models to learn from textual data, achieving effective feature extraction and improving prediction accuracy.
  3. Handling Class Imbalance:
     Techniques such as class weighting and L1/L2 regularization were employed to address the class imbalance in the dataset and prevent overfitting.
  4. Performance Evaluation:
     Validation metrics include accuracy, AUC-ROC curves, and loss trends. Strategies such as dropout, batch normalization, and learning rate scheduling were used to achieve better generalization.

# Technologies Used

  1. Python: Main programming language used for model development and preprocessing.
  2. TensorFlow/Keras: Frameworks used to build and train the deep learning models.
  3. Pandas, NumPy, and Scikit-Learn: Tools for data manipulation, feature engineering, and preprocessing.
  4. Matplotlib: Visualized model performance metrics, including accuracy and loss curves.

     
# Project Highlights

Glaucoma Detection from Text: The project leverages deep learning to classify the presence of glaucoma from clinical notes, a novel approach in the field of medical AI.
Model Optimization: Implemented various optimization techniques such as learning rate decay, early stopping, and model checkpointing to ensure the best model performance while preventing overfitting.
Generalization Improvements: L1 and L2 regularization were used to prevent overfitting and maintain model generalization, ensuring the model performs well on unseen data.
