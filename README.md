# Disease Outbreak Prediction

This project uses the Naive Bayes algorithm to predict disease outbreaks based on historical data. The aim is to provide a tool for early warning and effective response to potential outbreaks.

## Demo Screenshot
![Demo Screenshot](C:\Users\Sugavaneshwaran\Downloads\Compressed\Diseaseprediction-master\Diseaseprediction-master\image.png)

## Features

- Data preprocessing
- Model training using Naive Bayes
- Prediction of disease outbreaks
- Visualization of results

## Requirements

- Python 3.6+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Setup

Follow these steps to get the project up and running on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/disease-outbreak-prediction.git
cd disease-outbreak-prediction
2. Create a Virtual Environment
bash
Copy code
python3 -m venv env
source env/bin/activate
On Windows, use:

bash
Copy code
env\Scripts\activate
3. Install Dependencies
bash
Copy code
pip install -r requirements.txt
If requirements.txt is not available, manually install the dependencies:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib
4. Run the Prediction Script
bash
Copy code
python disease_prediction.py
Directory Structure
Copy code
disease-outbreak-prediction/
│
├── disease_prediction.py
├── Testing.csv
├── README.md
├── requirements.txt
└── LICENSE
Usage
Ensure your dataset (Testing.csv) is placed in the root directory of the project.
Run the prediction script as shown above.
View the predictions and visualize the results.
Configuration
Make sure the dataset file Testing.csv is formatted correctly and located in the root directory.

License
This project is licensed under the Creative Commons Zero Universal License - see the LICENSE file for details.