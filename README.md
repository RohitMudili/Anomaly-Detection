# Maritime Vessel Anomaly Detection

This project implements an advanced anomaly detection system for maritime vessel tracking data using machine learning techniques. The system analyzes vessel movement patterns to identify potential anomalies in ship behavior.

## Overview

The project uses various parameters from vessel tracking data including:
- Latitude
- Longitude
- Speed
- Course
- Heading

The system processes this data to detect anomalous behavior that might indicate:
- Unusual navigation patterns
- Suspicious vessel movements
- Potential safety concerns

## Technologies Used

- Python 3.x
- Key Libraries:
  - pandas - Data manipulation and analysis
  - numpy - Numerical computations
  - tensorflow/keras - Deep learning models
  - scikit-learn - Machine learning utilities
  - matplotlib - Data visualization
  - PyTorch - Deep learning framework

## Setup

1. Clone the repository:
```bash
git clone https://github.com/RohitMudili/Anomaly-Detection.git
cd Anomaly-Detection
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib sklearn tensorflow torch beautifulsoup4 requests
```

3. Place your vessel tracking data in CSV format with the following columns:
   - timestamp (as index)
   - latitude
   - longitude
   - speed
   - course
   - heading
   - anomaly (target variable)

## Usage

The main analysis is contained in the Jupyter notebook `Anomaly_detector(Yellow_Alert).ipynb`. To use:

1. Open the notebook in Jupyter Lab/Notebook
2. Follow the cells in sequence:
   - Data loading and preprocessing
   - Model training
   - Anomaly detection
   - Results visualization

## Data Format

The input data should be a CSV file with the following structure:

| timestamp           | latitude  | longitude   | speed | course | heading | anomaly |
|-------------------|-----------|-------------|-------|--------|---------|---------|
| YYYY-MM-DD HH:MM:SS | float     | float       | float | float  | float   | binary  |

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Author

Rohit Mudili 