# smoker-nonsmoker-face-wrinkle-cnn
This project aims to classify facial images as "Smoker" or "Non-Smoker" by analyzing wrinkle patterns using computer vision and deep learning. The workflow includes face detection, alignment, wrinkle map extraction using a Hybrid Hessian Filter, and classification using a Convolutional Neural Network (CNN). 

---
The project demonstrates practical applications of image processing, feature engineering, and model evaluation in Python.
---

## Features

- **Automatic dataset extraction** from ZIP file
- **Face detection and alignment** using MTCNN and OpenCV Haar Cascades
- **Wrinkle map extraction** using Hybrid Hessian Filter
- **Data visualization** for wrinkle maps and model performance
- **CNN-based classification** of smoker vs non-smoker faces
- **Performance metrics**: accuracy, confusion matrix, classification report

---

## Folder Structure

```
.
├── data/                   # Extracted dataset (smoker/non-smoker images)
├── aligned_faces/          # Aligned face images (optional output)
├── DAV lab/                # Main project folder
│   └── dav2.ipynb          # Main Jupyter notebook
├── README.md               # Project documentation
```

---

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/smoker-nonsmoker-face-wrinkle-cnn.git
   cd smoker-nonsmoker-face-wrinkle-cnn
   ```

2. **Install dependencies**
   ```bash
   pip install numpy pandas matplotlib opencv-python mtcnn scikit-learn seaborn tensorflow
   ```

3. **Place your dataset**
   - Put your zipped dataset as `DATA SET.zip` in the project root.
   - The notebook will automatically extract it to the `data/` folder.

4. **Run the notebook**
   - Open `dav2.ipynb` in VS Code or Jupyter Notebook.
   - Execute cells sequentially.

---

## Usage

- **Face Detection & Alignment:**  
  Detects and crops faces from images using MTCNN or Haar Cascades.

- **Wrinkle Map Extraction:**  
  Applies Hybrid Hessian Filter to highlight wrinkle patterns.

- **Visualization:**  
  Displays sample wrinkle maps for both classes.

- **Model Training:**  
  Trains a CNN to classify images based on wrinkle features.

- **Evaluation:**  
  Shows accuracy, confusion matrix, and sample predictions.

---

## Example Results

- **Wrinkle Map Visualization:**  
  ![Sample Wrinkle Maps](sample_wrinkle_maps.png)

- **Confusion Matrix:**  
  ![Confusion Matrix](confusion_matrix.png)

---

## Key Files

- `dav2.ipynb` : Main notebook with all code and explanations.
- `DATA SET.zip` : Zipped dataset containing smoker and non-smoker images.

---

## References

- [MTCNN Face Detector](https://github.com/ipazc/mtcnn)
- [OpenCV](https://opencv.org/)
- [TensorFlow/Keras](https://www.tensorflow.org/)
- [Scikit-learn](https://scikit-learn.org/)

---

## Author

- Himanshu Maurya  
- Data Analytics and Visualization Lab, Semester 5

---

## License

This project is for educational purposes only.
