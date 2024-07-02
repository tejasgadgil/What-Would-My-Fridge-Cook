# What Would My Fridge Cook?
"What Would My Fridge Cook?" is a machine learning-based tool that recommends recipes based on user-provided ingredients. Utilizing a k-Nearest Neighbors (k-NN) model and implemented in Python with a Tkinter GUI, it helps users discover new recipes by suggesting those with similar ingredient lists.

## Problem Statement
Develop a recipe recommendation system that takes ingredients from the user as input and recommends a list of recipes that can be made using those ingredients. The system allows users to input a list of ingredients, specify the number of recipes to recommend, and display the recommended recipes with clickable links to the original recipe sources.

## Abstract
The "What Would My Fridge Cook?" system is a machine learning-based tool that recommends recipes based on a user's input list of ingredients. It employs a k-Nearest Neighbors (k-NN) model trained on a dataset of recipes and their associated ingredient lists. Users input a list of ingredients, specify the number of recipes to recommend, and the system displays the recommended recipes with clickable links to the original recipe sources. Implemented in Python with a Tkinter GUI, the recommendation algorithm processes the input list of ingredients and finds the k-nearest neighbors from the training dataset to recommend recipes with similar ingredient lists. This system is a valuable tool for home cooks and recipe enthusiasts.

## Dataset Resource
Author permitted for educational purposes: [RecipeNLG Dataset](https://recipenlg.cs.put.poznan.pl/dataset)

## Module-wise Description

### Module Imports
- `pandas`: Used for data manipulation and analysis.
- `CountVectorizer` from `sklearn.feature_extraction.text`: Converts text into a matrix of token counts.
- `NearestNeighbors` from `sklearn.neighbors`: Finds k-nearest neighbors based on a given distance metric.
- `tkinter`: Used for creating a graphical user interface (GUI).
- `webbrowser`: Opens URLs in the default browser.

## Libraries Used
- `Pandas`
- `Sklearn`
- `Tkinter`
- `Webbrowser`

## Getting Started
1. **Clone the repository**:
    ```bash
    git clone https://github.com/tejasgadgil/What-Would-My-Fridge-Cook.git
    cd what-would-my-fridge-cook
    ```
2. **Install the necessary libraries**:
    ```bash
    pip install pandas scikit-learn
    ```
3. **Run the application**:
    ```bash
    python main.py
    ```

## Usage
1. Enter the ingredients in the provided text box.
2. Use the slider to select the number of recipes you want to be recommended.
3. Click the "Recommended Recipes" button to see the list of recommended recipes.
4. Click on any recipe to open it in your default web browser.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
