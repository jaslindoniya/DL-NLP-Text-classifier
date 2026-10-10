# DL-NLP-Text-classifier

### What I did?
I built a Text Classifier using Deep Learning and NLP.

It can classify text like Spam vs Ham / Positive vs Negative.

### Tech Stack Used:
- **Python & PyTorch** for Deep Learning Model
- **TF-IDF Vectorizer** for Tokenize and Vectorize text (as per task)
- **Scikit-learn** for data splitting
- **Matplotlib** for plotting graphs

### Model Architecture:
- Input Layer: TF-IDF features (26)
- Hidden Layer 1: 64 neurons + ReLU + Dropout (0.3)
- Hidden Layer 2: 32 neurons + ReLU + Dropout (0.3)
- Output Layer: Sigmoid for classification
- I also added BatchNorm and Early Stopping concept

### Results:
- Model trained for 15 epochs
- Training Loss went from 0.69 to 0.66
- Validation Loss also decreasing, which means model is learning well
- Loss Convergence Curve is plotted as proof

### How to Run?
1. Open the `Task_05.ipynb` in Google Colab
2. Run all cells
3. You will get the Loss Convergence Curve and Sample Predictions with confidence

### Sample Output:
`I love this` -> Positive with 0.52 confidence
`free lottery spam` -> Negative with 0.45 confidence

Completed as part of RabTech Internship - AI/ML Domain.
