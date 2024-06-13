
# Smartwatch Gestures Analysis

This repository contains an advanced-level analysis of the Smartwatch Gestures dataset using TensorFlow and various machine learning techniques.

## Files

- `Smartwatch_Gestures_Analysis.ipynb`: Jupyter Notebook with the analysis.

## Dataset

The Smartwatch Gestures dataset is a collection of time-series data used to evaluate gesture recognition algorithms. This dataset includes acceleration data from a 3-axis accelerometer for different arm gestures.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/debjit-mandal/Smartwatch-Gestures-Analysis.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Smartwatch_Gestures_Analysis.ipynb
   ```

3. Run the cells to perform the analysis.

## Analysis Steps

1. **Load Libraries**: Import necessary libraries including TensorFlow, TensorFlow Datasets, Pandas, NumPy, and Matplotlib.
2. **Dataset Inspection**: Load the dataset and convert it to a Pandas DataFrame for easier manipulation.
3. **Data Preprocessing**: Inspect the data and split it into training and test sets.
4. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of gestures in the training set.
   - Inspect and visualize sample gesture features.
5. **Feature Engineering**: Extract statistical features from the accelerometer data for model training.
6. **Model Training**:
   - Train a RandomForestClassifier on the extracted features.
   - Evaluate the model using classification report and confusion matrix.

## Results

The notebook provides detailed steps for loading, preprocessing, and analyzing the Smartwatch Gestures dataset. It includes visualizations and model evaluation metrics.

## License

This project is licensed under the MIT License.

----------------------------------------------------------------

Feel free to suggest any kind of improvements.