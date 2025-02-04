# SpaceX Falcon 9 First Stage Landing Prediction

## Overview
This project predicts whether the SpaceX Falcon 9 first stage will successfully land using machine learning models. By analyzing data collected from the SpaceX API, the project provides insights into landing outcomes, which are crucial for estimating launch costs and helping competitors make informed decisions when bidding for rocket launches.

## Dataset
Data is collected via API requests from SpaceX and includes key information about past rocket launches, such as:
- **Launch Date:** The date and time of the rocket launch.
- **Rocket Type:** Type and configuration of the rocket.
- **Launch Site:** Location of the launch.
- **Payload:** Information about the payload being delivered.
- **Landing Outcome:** Whether the first stage landed successfully or not.

## Key Objectives
1. Collect and clean launch data from the SpaceX API.
2. Perform exploratory data analysis (EDA) to uncover trends.
3. Build and evaluate machine learning models to predict landing success.

## Project Structure
```
.
├── README.md                 # Documentation file
├── SpaceX.ipynb              # Main analysis and prediction notebook
├── data/                     # Data collected from the SpaceX API
├── results/                  # Outputs such as model predictions and visualizations
└── models/                   # Trained models and related scripts
```

## Key Features
- **Data Collection:** Requests data from the SpaceX API and processes it for analysis.
- **Exploratory Data Analysis:** Visualizes and identifies key factors affecting landing success.
- **Machine Learning Models:** Trains models to predict whether the first stage will successfully land.
- **Cost Implication Analysis:** Highlights cost-saving opportunities based on prediction outcomes.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/spacex-landing-prediction.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and execute the `SpaceX.ipynb` notebook in a Jupyter environment to follow the analysis and predictions.

## Results
- Prediction of first stage landing success.
- Visualizations of launch trends and their impact on outcomes.
- Insights into cost-saving strategies for future launches.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, feel free to reach out:
- **Email:** Adam.RivardWalter@gmail.com  
- **GitHub:** [adamw80](https://github.com/adamw80)
