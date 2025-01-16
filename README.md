# Sleep Stage Classification

This Jupyter Notebook performs sleep stage classification using EEG data from the Sleep Physionet dataset. The notebook includes data loading, preprocessing, feature extraction, and classification steps.

## Steps
1. **Data Loading**: Load EEG data for two participants and preprocess it.
2. **Visualization**: Plot raw EEG signals and annotated events.
3. **Feature Calculation**: Compute power spectral density features for different frequency bands.
4. **Classification**: Train a Random Forest classifier on the features and evaluate its performance.
5. **Result Analysis**: Analyze the classification results using confusion matrix.

## Run Instructions
1. Clone the repository.
2. Create and/or activate a virtual environment
3. Install the required packages using `pip install -r requirements.txt`.
4. Open the Jupyter Notebook using `jupyter notebook`.
5. Run the cells sequentially to reproduce the results.
