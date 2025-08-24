# Potato Disease Classification 🌱🥔

This project uses **deep learning (CNNs with TensorFlow/Keras)** to
classify potato plant leaves into different disease categories. The
model is trained on the **PlantVillage dataset** and can detect whether
a potato leaf is healthy or infected by common plant diseases.

## 📂 Project Structure

-   `Potato_Dieases.ipynb` -- Main Jupyter notebook for training,
    validation, and testing the model.
-   `PlantVillage/` -- Dataset folder containing labeled potato leaf
    images.

## 🔧 Requirements

Make sure you have the following installed: - Python 3.8+ - TensorFlow -
NumPy - Pandas - Matplotlib

Install dependencies with:

``` bash
pip install tensorflow numpy pandas matplotlib
```

## 🚀 How to Run

1.  Clone this repository and open the notebook:

    ``` bash
    git clone <your-repo-url>
    cd potato-disease-detection
    jupyter notebook Potato_Dieases.ipynb
    ```

2.  Ensure the dataset (`PlantVillage`) is available in the project
    folder.

3.  Run all cells in the notebook to:

    -   Preprocess and split the dataset into train, validation, and
        test sets.
    -   Train a Convolutional Neural Network (CNN).
    -   Evaluate accuracy and visualize results.

## 📊 Model Training

-   Image size: **256x256**
-   Batch size: **32**
-   Epochs: **20**
-   Dataset split: **80% training / 10% validation / 10% testing**

The model is built using: - `tensorflow.keras.models` -
`tensorflow.keras.layers`

## 📈 Results

-   Displays random sample images with labels.
-   Provides training/validation accuracy and loss plots.
-   Evaluates final model on test set.

## 🌍 Applications

-   Early detection of potato plant diseases.
-   Can be extended to other crops using similar datasets.
-   Useful for farmers, researchers, and agricultural AI applications.


