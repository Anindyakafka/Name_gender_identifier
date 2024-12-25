# Gender Classification by Names

This repository contains a machine learning project focused on predicting gender based on names. The model is built using Python and popular data science libraries.

## Project Overview
The primary goal of this project is to classify names by gender using features derived from the names themselves. The workflow includes:

1. Data preprocessing and cleaning.
2. Feature extraction using methods like CountVectorizer and DictVectorizer.
3. Model training and evaluation using scikit-learn.

## Dataset
The dataset used for this project is named `Names_dataset.csv`. It includes:
- A list of names.
- Corresponding gender labels (e.g., Male, Female).

## Requirements
The project requires the following Python libraries:
- pandas
- numpy
- scikit-learn
- joblib

Install the dependencies using pip:
```bash
pip install pandas numpy scikit-learn joblib
```

## Usage
1. Clone the repository:
   ```bash
   git clone <https://github.com/Anindyakafka/Name_gender_identifier.git>
   ```

2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```

3. Run the Jupyter Notebook to execute the code:
   ```bash
   jupyter notebook "Gender Classification By Names.ipynb"
   ```

## Project Structure
- `Gender Classification By Names.ipynb`: Main notebook containing the code for preprocessing, training, and evaluation.
- `Names_dataset.csv`: Dataset used for training and testing the model.
- `README.md`: Documentation file for the project.

## Model Details
The model uses features extracted from names to predict gender. The pipeline includes:
- Data splitting into training and test sets using `train_test_split`.
- Feature extraction with `CountVectorizer`.
- Model training with scikit-learn classifiers.

## Future Work
- Improve model accuracy by experimenting with additional features.
- Expand the dataset to include more diverse names and genders.
- Integrate the model into a web or mobile application.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The dataset and inspiration for this project were drawn from public domain sources.
- Special thanks to the open-source community for providing the tools and libraries used in this project.

---
Feel free to contribute to this repository by submitting issues or pull requests!
