# Multi-Task Learning Example for Gender and Race Classification

This repository includes a multi-task learning example on the face images to classify the genders and races of people. The dataset is from the Kaggle.

The code has been written on GoogleColab. You just need to run the code in multi_task_learning.ipynb, the code first retrieve the data from Kaggle dataset including more than 20000 face images with the labels of gender, ethnicity, and age. We apply transfer learning by using VGG16 to classify the image genders and races. The accuracy is quite high and you can see that we use different evaluation techniques such as Receiver Operating Characteristic (ROC) curve and Area Under the Curve (AUC). 

In order to enhance accuracy, we have augmented the training data by applying data augmentation techniques. This code serves as a comprehensive implementation of multi-task learning and can be considered a small-scale project. Efforts have been made to mitigate overfitting and achieve relatively high accuracy on the data. However, it is important to note that the results may not represent the absolute best and further improvements can be made by expanding the dataset and modifying the network architecture.

Unfortunately, due to time constraints, detailed comments and additional descriptions are not included in the code. However, I am open to suggestions and feedback to make the repository more educational and beneficial for those interested in learning deep learning (DL) and machine learning (ML) applications.

I hope this repository proves useful to you. If you would like to contribute and help me, please feel free to contact me. Together, we can make the repositories more informative and valuable for anyone interested in DL and ML applications.

Thank you sincerely for your support.

Best regards.
