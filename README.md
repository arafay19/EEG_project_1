# EEG Emotion Recognition Data Processing

This project processes and analyzes EEG data for emotion recognition tasks. The workflow includes:

## Data Preparation
- Combines multiple EEG segment files into a single dataset
- Handles data from 6 different subjects
- Outputs a consolidated CSV file containing all EEG segments

## Data Analysis
- Examines dataset dimensions (1,598,968 rows × 31 columns)
- Analyzes emotion class distribution:
- Generates visualization of class distribution

## Data Processing
- Performs artifact filtering on the EEG data
- Maintains original emotion class balance after filtering
- Preserves all 5 emotion categories in the processed data

## Usage
1. Place EEG segment files in the working directory
2. Run the notebook cells sequentially to:
   - Combine individual EEG files
   - Analyze class distribution
   - Filter artifacts
   - Generate visualizations
3. Application of Principal Component Analysis (PCA) for dimensionality reduction.
4. Modeling the data using Support Vector Machines and a Fully Connected Feedforward Neural Network.

## Dependencies
- Python 3.x  
- pandas
- matplotlib
- seaborn
