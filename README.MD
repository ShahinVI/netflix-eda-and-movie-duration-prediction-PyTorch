# Exploratory Data Analysis on Netflix Movies from the 1990s

## Overview

This project performs an exploratory data analysis (EDA) on a dataset containing Netflix movies. The primary objective is to dive into the movie data, particularly focusing on movies released in the 1990s, and to gain insights into the trends, genres, directors, and more. The notebook is aimed at flexing analytical skills while exploring the entertainment industry.

This project uses Python and key data science libraries like Pandas and Matplotlib for analysis and visualization.

## Dataset

The dataset used in this project is `netflix_data.csv`, which contains the following columns:

| Column       | Description                  |
|--------------|------------------------------|
| `show_id`    | The unique ID of the show     |
| `type`       | The type of the show (Movie/TV Show) |
| `title`      | The title of the show         |
| `director`   | The director of the show      |
| `cast`       | The main cast of the show     |
| `country`    | Country of origin             |
| `date_added` | The date the show was added to Netflix |
| `release_year`| Year the show was released   |
| `duration`   | Duration of the show in minutes |
| `description`| A brief description of the show |
| `genre`      | The genre of the show         |

The dataset file is not provided in this repository due to size constraints. You will need to download the dataset separately and place it in the project root.

## Project Structure

The main analysis is contained within a Jupyter notebook (`notebook.ipynb`), which covers the following sections:

1. **Data Import & Cleaning**: Importing the dataset and handling any missing or inconsistent data.
2. **Exploratory Data Analysis (EDA)**: Generating descriptive statistics, visualizing trends in the data, and analyzing the main features such as genres, directors, and the distribution of movies released in the 1990s.
3. **Visualization**: Various plots and charts using Matplotlib to visualize trends and insights from the dataset.

## How to Run the Project

To run the project, ensure you have the required dependencies installed. You can install the dependencies using the following:

```bash
pip install -r requirements.txt

´´´

### Running the Jupyter Notebook

1. Ensure you have Jupyter installed by following the installation instructions in the official [Jupyter documentation](https://jupyter.org/install).
2. Start Jupyter by running the following command:

```bash
jupyter notebook

´´´

3. Open `notebook.ipynb` and run the cells to perform the analysis.

---

### Requirements

This project relies on the following Python libraries:

- **pandas**: For data manipulation and analysis
- **matplotlib**: For visualizations
- **seaborn**: For enhanced data visualizations
- **numpy**: For numerical computations
- **scikit-learn** (OneHotEncoder, train_test_split, cross_val_score, GradientBoostingRegressor, mean_absolute_error): For machine learning tasks like encoding and model training
- **torch (PyTorch)**: For building and training neural networks
- **copy**: For deep copying in Python (part of the standard library)

---

### License

This project is licensed under the MIT License - see the LICENSE file for details.

---

### Acknowledgments

The Netflix dataset used in this analysis was provided as part of the project and contains a wealth of information for exploration.
