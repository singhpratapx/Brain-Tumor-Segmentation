# Brain-Tumor-Segmentation
This project accurately classify brain tumors into four categories: glioma, meningioma, no tumor, and pituitary.  By leveraging a CNN I was able to design a robust and scalable solution for medical image classification. The model  demonstrated significant potential in aiding early diagnosis and providing  support to medical practitioners.
Dataset: The project will use publicly available MRI datasets containing
 brain tumor images.- Model:Implementation of the ResUNET architecture for segmenting
 tumors.- Preprocessing: Data augmentation, normalization, and resizing of MRI
 images.- Training & Validation: Model training with various hyperparameter
 tuning to achieve optimal results.- Evaluation: Quantitative evaluation using metrics such as Dice Score,
 Intersection over Union (IoU), Precision, and Recall.
 2 ToolsandTechnologies
 2.1 Python
 Python was the primary language used inthe projectdue to its versatility and rich ecosystem for machine learning. Libraries such as NumPy, Pandas, and OpenCV provided the 
 foundation for data handling and image preprocessing.
 2.2 TensorFlow/Keras
 The deeplearning models were implemented using TensorFlow and Keras, which offer high-level APIs for building neural networks. These libraries are particularly suited for
 designing complex architectures like ResUNet and for training models on large medical datasets.
 2.3 OpenCV
 The OpenCVlibrary wasusedfor imagepreprocessing tasks, including resizing, normalization, and data augmentation. These steps were crucial for preparing the MRI datasets 
 before feeding them into the neural network.
 2.4 JupyterNotebook
 Development and experimentation were conducted inJupyter Notebooks, providing a flexible environment for prototyping, visualizing, and debugging the model's performance.
 3. FutureEnhancements
 - Incorporate a more extensive and diverse dataset to improve the model’s generalization and accuracy.
 - Explore advanced architectures like transfer learning models (e.g., ResNet, EfficientNet) for potentially higher performance.
 - Extendtheprojecttoinclude tumor segmentation and localization for more detailed analysis.
 - Optimizethemodelfordeploymentonmobileor embedded devicesforon the-go diagnostics.
 In conclusion, this project serves as a foundational step towards integrating artificial intelligence into healthcare for brain tumor detection. While there is room for 
 further improvement, the outcomes achieved highlight the potential of AI in transforming diagnostic processes and enhancing medical decision making.
