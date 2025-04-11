

# 🐱🐶 Cat vs Dog Classification using MobileNetV2

This project classifies images of cats and dogs using **MobileNetV2**, a lightweight deep learning model optimized for mobile and embedded applications. By applying **transfer learning**, the model is fine-tuned on the cat-vs-dog dataset to achieve high accuracy with reduced training time and resource consumption.

## 🔍 Project Highlights

- Transfer learning with **MobileNetV2**  
- Binary image classification: **Cat vs Dog**  
- Efficient training with low computational cost  
- Training and validation accuracy/loss visualization  
- Real-time predictions on new images

## 🧠 Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Jupyter Notebook  


## 🧪 Model Architecture

- **Base Model**: `MobileNetV2` (pretrained on ImageNet)  
- **Top Layers**: GlobalAveragePooling → Dense (1 unit) with sigmoid  
- **Loss Function**: Binary Crossentropy  
- **Optimizer**: Adam  
- **Metrics**: Accuracy  


## ⚙️ Installation & Setup

```bash
git clone https://github.com/vir123-devf/cat-vs-dog-mobilenetv2.git
cd cat-vs-dog-mobilenetv2
jupyter notebook Cat_vs_Dog_Classification.ipynb
```

```python
plt.imshow(img)
plt.title(f"Prediction: {'Dog' if pred > 0.5 else 'Cat'}")
```

## 🤝 Contributing

Contributions and suggestions are welcome!  
Feel free to fork the repo, open an issue, or submit a pull request.

## 📄 License

This project is licensed under the **MIT License**.

This project is licensed under the **MIT License**.

## 🤝 Contributing

Contributions are welcome! Fork the repo and submit a PR.
