# ML - Decision Tree (Iris Dataset)

A simple and intuitive implementation of the **Decision Tree Classifier** using Python and Scikit-learn on the famous **Iris flower dataset**. This project demonstrates basic machine learning steps: data loading, preprocessing, model training, evaluation, and visualization.

## Features

- Loads and visualizes the Iris dataset
- Splits data into training and test sets
- Trains a Decision Tree Classifier using Scikit-learn
- Evaluates performance using accuracy and classification report
- Visualizes the trained decision tree

## 📊 Dataset: Iris

The Iris dataset is a classic dataset in machine learning that includes:

- 150 samples
- 3 classes: Setosa, Versicolor, Virginica
- 4 features: sepal length, sepal width, petal length, petal width

Loaded directly using `sklearn.datasets.load_iris()`.

## 🧠 Tech Stack

- **Python**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib**

## 🛠 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/ShridhiGupta/ML-Decision-Tree.git
   cd ML-Decision-Tree
   ```

2. **Install required libraries**
   *(If not already installed)*
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```

3. **Run the script**

   - Open the `.ipynb` file in Jupyter Notebook  
     **OR**  
   - Run the Python file directly (if available)

4. **Output**
   - Accuracy of the model
   - Classification report (precision, recall, f1-score)
   - A decision tree visualization plot

## 📸 Output Preview

![Decision Tree Visualization](assets/decision_tree_example.png)  
*Note: Add your plot screenshot in the `assets/` folder and name it accordingly.*

## 📈 Sample Results

```text
Accuracy: 1.0

Classification Report:
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        16
  versicolor       1.00      1.00      1.00        14
   virginica       1.00      1.00      1.00        15
```

## 🚀 Future Enhancements

- Add GUI using Streamlit for interactive predictions
- Allow input of custom flower measurements
- Add model comparison (e.g., Random Forest, KNN)

## License

This project is licensed under the [MIT License](LICENSE).

---

### Contributions

Have an idea to improve this? Feel free to fork the repo, open issues, or submit a pull request!  
If you found this helpful, don’t forget to ⭐ star the repository.

