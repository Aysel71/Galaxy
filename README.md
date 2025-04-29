# This repository was prepared by the team: Aysel Mirzoeva and Borisiuk Anna
# 🌌 Galaxy Image Classification
**📚 Course:** Deep Learning for Computer Vision  
**📝 Homework:** Galaxy Image Classification with Galaxy10 DECals Dataset
---

## 🎯 Objective
Train a deep learning model 🧠 to classify galaxy images 🌌 into one of 10 categories using the Galaxy10 DECals dataset.

✅ Successful completion: **Achieve >90% accuracy** on the test set.

---

## 📂 Dataset
**📛 Name:** Galaxy10 DECals  
**🔗 Source:** [Hugging Face Datasets - Galaxy10 DECals](https://huggingface.co/datasets/matthieulel/galaxy10_decals)

- 📸 **Total Images:** 17,736  
- 🖼️ **Image Size:** 256x256 pixels  
- 🎨 **Format:** RGB color images  
- 🏷️ **Classes:**  

| 🔢 Label | 🪐 Class Name                  |
|:-------:|:------------------------------:|
| 0        | Disturbed                     |
| 1        | Merging                       |
| 2        | Round Smooth                  |
| 3        | In-between Round Smooth       |
| 4        | Cigar Shaped Smooth            |
| 5        | Barred Spiral                  |
| 6        | Unbarred Tight Spiral          |
| 7        | Unbarred Loose Spiral          |
| 8        | Edge-on without Bulge          |
| 9        | Edge-on with Bulge             |

---

## 🛠️ Tasks
- 📥 Load and explore the dataset.
- 🧹 Preprocess the images (normalization, augmentations if necessary).
- 🏗️ Build and train a deep learning model (e.g., CNN).
- 📈 Evaluate the model:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion matrix
- 🏆 Target: **Accuracy > 90%** on the test split.

---

## 📦 Prerequisites
Install the required packages first:

```bash
!pip install datasets scikit-learn matplotlib numpy -q
```

> ⚠️ Note: Some minor dependency warnings may appear. They do not prevent the homework from being completed successfully!

### 📚 Imports
```python
import datasets
import numpy as np
import matplotlib.pyplot as plt
from sklearn.metrics import accuracy_score, precision_recall_fscore_support, confusion_matrix, ConfusionMatrixDisplay
```

---

## 👀 Visualization
Use helper functions to visualize galaxy classes and predictions:

```python
show_class_examples(dataset, class_names_map)
evaluate_predictions(predicted_labels, true_labels, class_names_list)
```

Functions provided include:
- **show_class_examples**: Displays a sample image for each galaxy class.
- **evaluate_predictions**: Calculates and plots evaluation metrics + confusion matrix.

---

## 📊 Metrics to Report
After evaluation, report:
- **Accuracy**
- **Weighted Precision, Recall, F1-Score**
- **Per-Class Precision, Recall, F1-Score**
- **Confusion Matrix**

> 🎯 Remember: **Accuracy must exceed 90%** to pass!

---

## 🚀 Progress
- ✅ Dataset loaded
- ✅ Preprocessing done
- ✅ Model defined and trained
- ✅ Achieved >90% accuracy

---

## 🌟 Conclusion
This project helps you practice applying deep learning techniques to real-world astronomical data 🌠 and strengthens your skills in image classification tasks!
