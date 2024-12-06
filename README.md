# Grape Quality Prediction

This project uses machine learning to predict the quality of grapes based on various factors like acidity, sugar content, and other chemical properties. It demonstrates the use of regression models to predict the quality of wine grapes from a dataset that contains information about different chemical features.

## Dataset

The dataset used for this project contains various chemical properties of grapes and the target variable is the quality score. Key features include:

- **Fixed Acidity**: Amount of tart taste.
- **Volatile Acidity**: Affects the taste and smell.
- **Citric Acid**: Contributes to the taste and freshness.
- **Residual Sugar**: Sugar remaining after fermentation.
- **Chlorides**: Salt concentration.
- **Free Sulfur Dioxide**: Preservative.
- **Total Sulfur Dioxide**: Overall sulfur content.
- **Density**: Weight of the liquid.
- **pH**: Measure of acidity.
- **Sulphates**: Impact on flavor.
- **Alcohol**: Alcohol content of the wine.
- **Quality**: Target variable, indicating the quality of the grape (1-10).

## Technologies Used

- **Python**: For data analysis and modeling.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-learn**: For implementing regression models.
- **Matplotlib** & **Seaborn**: For data visualization.

## Steps

1. **Data Preprocessing**: Clean and preprocess the data (handling missing values, encoding categorical variables, etc.).
2. **Model Training**: Use machine learning regression models (e.g., Decision Tree, Random Forest) to train the model on the dataset.
3. **Evaluation**: Evaluate the model using performance metrics such as R² score and Mean Absolute Error (MAE).
4. **Prediction**: Use the trained model to predict grape quality based on input features.

## How to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/alphacrypto246/Grape-Quality-Prediction.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:

    ```bash
    jupyter notebook main.ipynb
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

