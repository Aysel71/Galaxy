# This repository was prepared by the team: Aysel Mirzoeva and Borisiuk Anna
# 🌌 Galaxy Image Classification
**📚 Course:** Deep Learning for Computer Vision  
**📝 Homework:** Galaxy Image Classification with Galaxy10 DECals Dataset
---

## 🎯 Objective
Train a deep learning model 🧠 to classify galaxy images 🌌 into one of 10 categories using the Galaxy10 DECals dataset.

✅ Successful completion: **Achieve >87% accuracy** on the test set.

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
- 🏆 Target: **Accuracy > 87%** on the test split.
---

## 👀 Visualization
We use helper functions to visualize galaxy classes and predictions:

```python
show_class_examples(dataset, class_names_map)
evaluate_predictions(predicted_labels, true_labels, class_names_list)
```

Functions provided include:
- **show_class_examples**: Displays a sample image for each galaxy class.
- **evaluate_predictions**: Calculates and plots evaluation metrics + confusion matrix.

And wandb for logging and visualizing training/validation progress
---

## 📊 Metrics to Report
After evaluation, report:
- **Accuracy**
- **Weighted Precision, Recall, F1-Score**
- **Per-Class Precision, Recall, F1-Score**
- **Confusion Matrix**

> 🎯 Remember: **Accuracy must exceed 87%** to pass!

---
## 🚀 Progress
- ✅ Dataset loaded
- ✅ Preprocessing done
- ✅ Model defined and trained
- ✅ Achieved >87% accuracy(resnet_advanced)
- there were more notebooks but some of them were lost as too much of them were made but it and ensembles reached on the 20 epoch the score also equals; to the 0,88
- we also have teh notebook best_zoobot_convnext (1) (1).ipynb that achieved 0,89 but as we hae run out of resourses we could not run it agian to show what we have reached but if u do not believe u can run it again) 
---

---


## 🌟 Conclusion
This project helps you practice applying deep learning techniques to real-world astronomical data 🌠 and strengthens your skills in image classification tasks!

You can find full training logs and metrics at [Galaxy10 Classification WandB Project](https://wandb.ai/a8or1suk-skoltech/galaxy10_classification/reports/Galaxy10-Experiments--VmlldzoxMjUyODMwNQ?accessToken=957u51spii30qq8e1giskwvc214wqxohxaukwwe15vnyqr0cm45pf5545derlm7h).

