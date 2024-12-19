This project implements an image classification model using the CIFAR-10 dataset by comparing MLP based models, and CNN. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The goal of this project is to build a deep learning model to classify these images into the appropriate categories.
Also , implemented K-Means algorithm from scratch.
## Dataset

The dataset used in this project is the CIFAR-10 dataset, which is publicly available and can be downloaded from [here](https://www.cs.toronto.edu/~kriz/cifar.html).

- **Number of Classes**: 10 (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
- **Images per Class**: 6,000
- **Image Size**: 32x32 pixels (color images)

## Technologies Used

- **Deep Learning Framework**: PyTorch
- **Programming Language**: Python
- **Data Processing**: NumPy, Pandas
- **Visualization**: Matplotlib, Seaborn
- **Version Control**: Git
- **Repository Hosting**: GitHub

## Model Performance

### MLP-based Model:
- **Test Accuracy**: 81%
- **F1 Score**: 0.82

### CNN-based Model:
- **Test Accuracy**: 87.2%
- **F1 Score**: 0.872
