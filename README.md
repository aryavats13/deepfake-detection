# 🎭 DeepFake Detection (ResNet + LSTM)

Detect face-swap deepfakes using a hybrid model that combines ResNet for feature extraction and LSTM for sequence learning.

## 🚀 Setup

```bash
git clone https://github.com/yourusername/deepfake-detector.git
cd deepfake-detector
pip install -r requirements.txt
```

## 🗂️ Dataset

Organize images like this:

```
data/
├── real/
├── fake/
```

## 🏋️ Training

```bash
python train.py
```

## 📈 Testing

```bash
python test.py
```

## 🔍 Prediction

```bash
python predict.py
```

## 🌐 Web App

```bash
streamlit run app.py
```

## 📦 Requirements

- tensorflow  
- opencv-python  
- numpy  
- pandas  
- scikit-learn  
- streamlit  


# deepfake-detection
deep fake detection using resnet50 and LSTM
data used - https://drive.google.com/open?id=10NGF38RgF8FZneKOuCOdRIsPzpC7_WDd
