# Chicago Crime Data Analysis

This repository contains Jupyter Notebooks for analyzing Chicago crime data using the PandasAI, a GPT powered data analysis tool. The project involves retrieving crime data from online sources and performing various analyses to gain insights into crime patterns in Chicago.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Notebooks](#notebooks)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Chicago Crime Data Analysis project aims to provide a comprehensive analysis of crime data in Chicago. The project includes retrieving data from online sources, processing and cleaning the data, and performing various analyses to identify trends and patterns.

## Project Structure

The project is organized into the following directories and files:
chicago-crime-data-analysis/
│
├── notebooks/
│   ├── chicago_crime_get_data.ipynb
│   ├── chicago_crime_chat.ipynb
│
├── data/
│   └── --data--.csv (unzip from project zip file, change path to fit.)
│
├── README.md

- `notebooks/`: Contains Jupyter Notebooks for data retrieval and analysis.
- `data/`: Directory for storing raw and processed data files.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python packages.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/chicago-crime-data-analysis.git
    cd chicago-crime-data-analysis
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```


## Usage

To use the notebooks, follow these steps:

1. Ensure the virtual environment is activated.

2. Start Jupyter Notebook:
    ```sh
    jupyter notebook
 
3. Create a `.env` file and add the necessary keys (see [Environment Variables](#environment-variables) section).   ```

4. Open and run the notebooks in the `notebooks/` directory to retrieve and analyze the Chicago crime data.

## Notebooks

### chicago_crime_get_data.ipynb

This notebook is responsible for retrieving crime data from online sources. It includes steps for:

- Fetching data from the Chicago Data Portal.
- Processing and cleaning the data.
- Saving the cleaned data to a CSV file.

### chicago_crime_chat.ipynb

This notebook performs various analyses on the retrieved crime data. It includes:

- Visualizing crime trends over time.
- Analyzing the distribution of crime types.
- Identifying crime hotspots in the city.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.