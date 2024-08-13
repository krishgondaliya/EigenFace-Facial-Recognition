# EigenFace-Facial-Recognition

Eigenfaces Face Recognition Project

This project implements the Eigenfaces algorithm using C++ and Python for face recognition. Eigenfaces is a computer vision approach that uses Principal Component Analysis (PCA) to reduce the dimensionality of facial images, allowing for efficient face recognition by projecting the images into a lower-dimensional space.

Features:
Face Recognition: Implements the Eigenfaces algorithm to recognize and classify faces from a given dataset.
Dimensionality Reduction: Uses PCA to reduce the dimensionality of facial images, capturing the most significant features that distinguish faces.
Visualization: Displays the Eigenfaces (principal components) and reconstructs images from the reduced feature set for analysis and debugging.
Multilingual Support: The project is implemented in both C++ and Python, providing flexibility in language preference and integration with other systems.


Dataset Preparation: Organize your facial images into a folder, with each subfolder named after the person in the images. The project will automatically process and recognize faces based on these labels.
Training: The algorithm will automatically train on the provided dataset, calculating the principal components and projecting the images into the reduced space.
Recognition: After training, the project can recognize new images by projecting them into the same reduced space and comparing them with the stored eigenfaces.


Accuracy: The project achieves a high level of accuracy on well-lit, front-facing images. Performance may vary based on the quality and diversity of the dataset.
Eigenfaces Visualization: The project can visualize the calculated eigenfaces, showing the principal components that contribute to face recognition.
Reconstruction: Images can be reconstructed from their reduced representations to verify the effectiveness of the dimensionality reduction.

Contributions are welcome! Please fork the repository and submit a pull request with your improvements or bug fixes.

Installation:
Python: Version 3.6 or later.
OpenCV: Install OpenCV for both C++ and Python.
Clone the Repository
Build and Run (C++)
Compile the C++ code: g++ -o eigenfaces eigenfaces.cpp `pkg-config --cflags --libs opencv4`


