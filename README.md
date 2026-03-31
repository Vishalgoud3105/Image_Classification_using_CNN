<h1 align="center">🖼️ CIFAR-10 Image Classification using CNN</h1>

<h3>🧩 Problem Statement</h3>
<blockquote>
In the field of computer vision, accurate image classification is critical for applications ranging from autonomous vehicles to healthcare. This project aims to build a deep learning model that can classify images from the CIFAR-10 dataset — a widely used dataset for benchmarking image classification tasks. The challenge is to develop a robust Convolutional Neural Network (CNN) that can learn to identify 10 mutually exclusive object categories from low-resolution images.
</blockquote>

<h3>💡 Project Description</h3>
<blockquote>
The CIFAR-10 dataset contains <strong>60,000 32x32 color images</strong> across <strong>10 classes</strong>, with 6,000 images per class. The dataset is split into <strong>50,000 training</strong> and <strong>10,000 test images</strong>. Each image is categorized as one of the following:
<ul>
  <li>✈️ Airplane</li>
  <li>🚗 Automobile</li>
  <li>🐦 Bird</li>
  <li>🐱 Cat</li>
  <li>🦌 Deer</li>
  <li>🐶 Dog</li>
  <li>🐸 Frog</li>
  <li>🐴 Horse</li>
  <li>🚢 Ship</li>
  <li>🚚 Truck</li>
</ul>
The model uses a CNN architecture implemented using TensorFlow’s Keras API. It is trained to identify these categories with high accuracy. 
</blockquote>

<h3>🛠️ Technical Stack</h3>
<blockquote>
<ul>
  <li><strong>Language:</strong> Python</li>
  <li><strong>Frameworks & Libraries:</strong> TensorFlow, Keras, NumPy, Matplotlib</li>
  <li><strong>Dataset:</strong> CIFAR-10 (imported using <code>tensorflow.keras.datasets</code>)</li>
  <li><strong>Development Platform:</strong> Google Colab / Jupyter Notebook</li>
</ul>
</blockquote>

<h3>⚙️ Steps Followed</h3>
<blockquote>
<ol>
  <li>📥 <strong>Import & Load Dataset</strong>: CIFAR-10 data loaded from TensorFlow</li>
  <li>🧼 <strong>Data Preprocessing</strong>:
    <ul>
      <li>Normalized pixel values (0–255 → 0–1)</li>
      <li>Labels converted to categorical format</li>
      <li>Data reshaped as needed for CNN input</li>
    </ul>
  </li>
  <li>🏗️ <strong>Model Building</strong>: 
    <ul>
      <li>Sequential CNN with Conv2D → MaxPooling → Dropout</li>
      <li>Dense layers for classification with Softmax output</li>
    </ul>
  </li>
  <li>🧠 <strong>Model Training</strong>: Trained using 10 epochs with Adam optimizer and categorical cross-entropy loss</li>
  <li>📊 <strong>Model Evaluation</strong>: 
    <ul>
      <li>Loss vs Validation Loss</li>
      <li>Accuracy vs Validation Accuracy</li>
    </ul>
  </li>
  <li>🔍 <strong>Testing & Predictions</strong>:
    <ul>
      <li>Predictions generated on test set</li>
      <li>Confusion Matrix and Classification Report calculated</li>
    </ul>
  </li>
</ol>
</blockquote>

<h3>📈 Results</h3>
<blockquote>
<ul>
  <li>✅ Achieved ~87% accuracy using CNN on CIFAR-10</li>
  <li>🔄 MaxPooling and Dropout improved generalization and reduced overfitting</li>
</ul>
</blockquote>

<h3>🚀 How to Run</h3>
<blockquote>
1. Clone the repository  
2. Open the Jupyter/Colab notebook  
3. Run each cell in order to preprocess, train, and evaluate the model  
4. Modify or experiment with the CNN layers to improve performance
</blockquote>

<h3>📦 Dataset Access</h3>
<blockquote>
Dataset is available via TensorFlow:
<pre>
from tensorflow.keras.datasets import cifar10  
(x_train, y_train), (x_test, y_test) = cifar10.load_data()
</pre>
</blockquote>

<h3>🔗 Credits</h3>
<blockquote>
Developed by <strong>C. Vishal Goud</strong> as part of the Artificial Intelligence Major Project, November Batch-2023  
CIFAR-10 Dataset: Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton
</blockquote>

---

<div align="center">

**Built with 💻 and ☕ by Vishal Goud**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](http://www.linkedin.com/in/vishalgoud3105)
[![GitHub](https://img.shields.io/badge/GitHub-black?style=flat&logo=github)](https://github.com/Vishalgoud3105)
[![Portfolio](https://img.shields.io/badge/Portfolio-orange?style=flat)](https://vishalgoud3105.github.io/Portfolio/)

---

### 📬 Contact

This repository is **private**. For collaboration inquiries, demo requests, or questions:

📧 **Email**: [vishalgoud3105@gmail.com](mailto:vishalgoud3105@gmail.com)  
💼 **LinkedIn**: [vishalgoud](http://www.linkedin.com/in/vishalgoud3105)  
🌐 **Portfolio**: [vishalgoud3105.github.io](https://vishalgoud3105.github.io/Portfolio/)

⭐ **Interested in this project? Reach out!** ⭐
