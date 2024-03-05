<h2>CNN Algorithms for Pneumonia Detection</h2>
<p>This notebook is dedicated to the application of classical Convolutional Neural Networks (CNN) for detecting pneumonia from chest X-ray images. It involves a comprehensive workflow including image preprocessing, CNN model design and training, followed by performance evaluation through various metrics and visualizations. The classical CNN model's effectiveness is tested on images reduced to 8 pixels, simulating a scenario with a significantly constrained number of features, revealing an accuracy of 56.25% across different train-test splits.</p>

<b>Libraries used:</b>
<ul>
  <li>matplotlib.pyplot for plotting and visualizations</li>
  <li>numpy for numerical computations</li>
  <li>torch, torchvision, and torchaudio for deep learning model construction and training</li>
</ul>

<h2>QCNN Code for Pneumonia Detection</h2>
<p>Exploring an experimental and innovative approach, this notebook integrates quantum computing principles with classical machine learning techniques to tackle pneumonia detection from chest X-ray images. Employing a hybrid methodology, the Quantum Convolutional Neural Network (QCNN) showcases a novel architecture that incorporates quantum circuits and classical preprocessing. The QCNN model outperforms its classical counterpart with accuracies of 75%, 73%, 75%, and 73% for test sizes of 0.15, 0.30, 0.40, and 0.50, respectively, on images reduced to 8 pixels.</p>

<b>Libraries used:</b>
<ul>
  <li>qiskit for implementing quantum circuits and algorithms</li>
  <li>qiskit_machine_learning for constructing quantum neural networks</li>
  <li>matplotlib.pyplot for visualizations</li>
  <li>numpy for data manipulation</li>
  <li>sklearn for classical machine learning utilities</li>
  <li>pandas for data handling</li>
  <li>opencv-python (cv2) and PIL for image processing</li>
</ul>

<b>Key Findings and Contributions:</b>
<ul>
  <li>The QCNN model demonstrates consistent accuracy levels across different train-test splits, indicating its robust performance even with limited training data. However, it's important to note the significantly longer training time required for QCNN compared to the classical CNN. Despite this trade-off, the QCNN model's ability to maintain accuracy with a reduced number of features emphasizes its potential in enhancing quantum-enhanced image classification techniques.</li>
</ul>

<b>Comparative Analysis:</b>
<ul>
  <li>The comparison between the classical CNN and QCNN models on the pneumonia dataset with the number of features reduced to both 8 and 6 pixels showcases the QCNN's superior performance. This study illustrates QCNN's potential advantages in computational efficiency and accuracy for image classification tasks, particularly in contexts where data availability is constrained or feature extraction is challenging.</li>
</ul>
