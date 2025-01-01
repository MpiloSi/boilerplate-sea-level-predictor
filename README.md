# Sea Level Predictor

The Sea Level Predictor project analyzes historical sea level data and predicts future sea level changes through the year 2050. This project uses Python libraries such as Pandas, Matplotlib, and SciPy to visualize data trends and make predictions based on historical sea level changes.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Functionality](#functionality)
- [Contributing](#contributing)
- [License](#license)

## Features

- Visualize historical sea level data using scatter plots.
- Calculate and plot lines of best fit for predictions.
- Predict future sea level changes through 2050 based on historical trends.
  
## Technologies Used

- Python 3.x
- Pandas for data manipulation
- Matplotlib for plotting
- SciPy for statistical analysis

## Installation

To run this project, you need to have Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

### Step 1: Clone the Repository

git clone https://github.com/freeCodeCamp/boilerplate-sea-level-predictor.git
cd boilerplate-sea-level-predictor


### Step 2: Install Dependencies

You will need to install the required libraries. You can do this using pip:

pip install pandas matplotlib scipy


## Usage

To use the Sea Level Predictor, run the `main.py` script. This script will execute the analysis and generate visualizations based on the sea level data.

### Example Command Line Usage

1. Open your terminal or command prompt.
2. Navigate to the project directory.
3. Run the following command:
   python main.py


## Functionality

The main functionalities of this project include:

1. **Data Loading**: The program reads sea level data from `epa-sea-level.csv`.
2. **Data Visualization**:
   - Creates a scatter plot of historical sea level data.
   - Calculates and plots a line of best fit using all available data.
   - Calculates and plots a second line of best fit using data from the year 2000 onward.
3. **Future Predictions**: Extends the lines of best fit to predict sea level changes through the year 2050.
