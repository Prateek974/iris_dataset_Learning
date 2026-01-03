# 🌸 Iris Species Classifier
This project implements a 3-layer Neural Network to classify Iris flowers. It includes a training pipeline in Python (TensorFlow)
## 🧠The Neural Network Architecture
### Model Architecture
**Input Layer**: 4 features (Sepal/Petal dimensions).

**Hidden Layer**: 8 Neurons with ReLU activation.

**Output Layer**: 3 Neurons (Softmax) for species classification.

**Optimization**: Adam Optimizer ($learning\_rate=0.01$) with Sparse Categorical Crossentropy loss

## 📈Performance
After training for 1,000 epochs(I know, a bit Overkill😂), the model achieved:

**Training Accuracy**: 96.67%

**Validation Accuracy**: 100%

**Test Loss**: 0.2955


