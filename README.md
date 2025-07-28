# 🧠 Visualization of Neural Network Loss Surface

This Machine Learning project explores how modifying individual weights of a neural network affects its performance. Using `MLPClassifier` on the **Iris dataset**, we developed an **interactive tool** that visualizes the effect of varying a single weight on model loss using insightful plots.

---

## 📌 Project Highlights

- 🎯 **Objective**: Analyze and visualize how a single neural network weight impacts loss/error.
- 📊 **Visualization**: Dynamic surface/line plots representing error changes.
- 🔍 **Interactivity**: Select any weight from `W1` or `W2` and vary it across a precision range.
- 🌸 **Dataset**: Classic Iris dataset (3 classes, 4 features).
- 🧠 **Model**: `MLPClassifier` with 1 hidden layer from `scikit-learn`.

---

## 🛠️ How It Works

1. Train a basic neural network on the Iris dataset.
2. Select a single weight from:
   - `W1` (input → hidden layer)
   - `W2` (hidden → output layer)
3. Sweep the chosen weight across a defined range (e.g., `-2.0` to `+2.0`).
4. For each step, observe how the model's prediction error changes.
5. Visualize the error surface using 2D/3D plots.

---

## 🖼️ Screenshots

### 🔹 Surface Plot for Varying W1

![W1 Plot](https://github.com/siddharth4096/neural-network-loss-visualization/blob/643146f781de76edbb033e56f2d31c4958df22f7/output.png)

---

## 🧰 Tech Stack

- **Python**
- **Jupyter Notebook**
- `scikit-learn` (MLPClassifier)
- `matplotlib` / `plotly` (visualization)
- `NumPy`, `Pandas`

---

## 📂 Project Structure

```
📁 neural-network-loss-visualizer/
├── model_training.ipynb        # Main Jupyter notebook with training and visualization
├── utils.py                    # Optional: Helper functions for plotting or analysis
├── images/                     # Folder for screenshots/plots
├── README.md                   # This file
```

---

## 🚀 Future Enhancements

- [ ] Extend to **2D weight variation** (heatmaps/surface plots)
- [ ] Create an interactive **web interface** for weight selection & visualization
- [ ] Apply to **larger datasets** and deep architectures

---

## 📚 References

- [📘 MLPClassifier Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html)
- [🌸 Iris Dataset - UCI Repository](https://archive.ics.uci.edu/ml/datasets/iris)

---

## 👨‍💻 Author

**Siddharth Kakoti**  
📎 GitHub: [siddharth4096](https://github.com/siddharth4096)

---

## 🔗 GitHub Repository

> 📍 [View the Project on GitHub](https://github.com/siddharth4096/iris-neural-network-app)

---

## 📢 More ML Projects Coming Soon!

Stay tuned! Exciting new projects involving neural networks and interactive visualization are on the way 🚀

If you liked this, don’t forget to ⭐ the repo!
