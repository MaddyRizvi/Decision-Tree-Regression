
# Decision Tree Regression – Truth or Bluff

This repository demonstrates the implementation of a Decision Tree Regression model to predict salaries based on position levels using a dataset `Position_Salaries.csv`. The project includes model training, prediction, and high-resolution visualization.

## 📁 Project Structure

```
.
├── Position_Salaries.csv
├── decision_tree_model.py
└── README.md
```

## 📦 Requirements

Ensure you have Python 3.7+ installed. Install the required packages with:

```bash
pip install -r requirements.txt
```

**Contents of `requirements.txt`:**

```txt
numpy
pandas
matplotlib
scikit-learn
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/MaddyRizvi/Decision-Tree-Regression.git
cd decision-tree-salary-prediction
```

2. Ensure `Position_Salaries.csv` is in the same directory.

3. Run the Python script:

```bash
python decision_tree_model.py
```

## 🧠 What It Does

- Loads and preprocesses data
- Trains a Decision Tree Regression model
- Predicts salary for a given position level (e.g., 6.5)
- Visualizes the decision tree predictions in high resolution

## 📈 Sample Output

- Prediction for level `6.5`
- Visualization showing predicted stepwise function vs actual salaries
- Visualising the Decision Tree Regression results (higher resolution)
![Image](https://github.com/user-attachments/assets/1ba9a89c-c017-489c-b742-a5ccc0879cbd)

## 🤝 How to Contribute

Contributions are welcome! Follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit: `git commit -m 'Add new feature'`
4. Push to your branch: `git push origin feature-name`
5. Open a Pull Request

Please follow the existing code style and add comments where necessary.

## ✅ TODO

- Add model evaluation metrics
- Allow input from users via CLI
- Compare with other regression models

## 📄 License

This project is licensed under the [MIT License](LICENSE).
