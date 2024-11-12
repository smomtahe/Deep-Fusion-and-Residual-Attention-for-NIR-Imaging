Deep Fusion and Residual Attention for NIR Imaging

Overview: This repository contains the implementation of an advanced deep learning model designed to enhance medical imaging. The project focuses on the integration of deep convolutional neural networks with fusion and residual attention mechanisms to improve the accuracy and efficiency of image reconstruction.

Key Features
-Dual Input Processing: Utilizes NIR reflectance data from two different LED sources to ensure comprehensive feature capture.
-Residual Attention Mechanism: Incorporates squeeze-and-excite blocks within residual attention frameworks to enhance feature importance dynamically.
-Deep Fusion Strategy: Employs a fusion layer that effectively combines features extracted from dual inputs, optimizing the image reconstruction process.
-Advanced Performance Metrics: Implements metrics such as RMSE (Root Mean Square Error), MAE (Mean Absolute Error), and PSNR (Peak Signal-to-Noise Ratio) to evaluate model performance.

Model Architecture: The model architecture is designed with a focus on handling the complexities of NIR data. It uses convolutional layers tailored to process one-dimensional reflectance data, transforming it through a series of attention-enhanced convolutional layers before reconstructing the final image output. The architecture emphasizes the ability to detect subtle features in images that are crucial for accurate diagnostics.
