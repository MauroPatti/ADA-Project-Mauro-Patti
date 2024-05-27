This project aims to analyze oncological data and images to train machine learning and deep learning algorithms for binary classification 
of benign and malignant cancers. Specifically, the datasets used consist of a CSV file containing numerical data extracted from tumor images,
representing mostly geometric features of the tumor mass. (https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset) 
and on the other side, hundreds of tumor images have been analyzed, both in grayscale and black and white, called masks.
(https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset).

The project starts with an exploratory analysis of the data, accompanied by principal component analysis and k-means clustering.
Subsequently, other models such as linear regression, lasso, principal component regression, support vector machines, 
classification trees, and random forests are employed. All results are evaluated using metrics such as accuracy and confusion matrix, 
and parameter tuning is often proposed, including tree depth, model complexity, lasso alpha, or SVM kernel.

Subsequently, the images from the other dataset were analyzed, and convolutional neural networks were trained using packages
such as Keras, TensorFlow, and PyTorch with 10 or 20 epochs for binary classification. There are two separate folders containing images: 
one for MASK images and the other for grayscale images.

The results highlighted the importance of the tumor mass structure in predicting its nature,
aiming to be a straightforward application of machine learning in the oncological field.





