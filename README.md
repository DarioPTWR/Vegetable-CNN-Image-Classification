# 🥬 Vegetable-CNN-Image-Classification

This CNN Image Classification project involves implementing an image classifier using a deep learning network. Given colored images of 224 by 224 pixels, containing 15 types of vegetables, the images must be :

- Converted to grayscale (using one channel only)
- Resized to 31 by 31 pixels
- Resized to 128 by 128 pixels

In this project, various types of CNN models were tested, such as Fully Connected Neural Network Model, Conv2D NN, Custom VGG, Custom AlexNet and a self-designed CNN model. For both input sizes, it was discovered that CustomVGG achieved the best accuracies, 96% and 99% for both image sizes respectively.

For further refinement in future, the model's performance could be further enhanced by testing with more architectures and implementing other hyperparameter tuning variables. However, judging from the current level of accuracy provided by the model, it can be concluded that the model has generalized well to unseen data and is able to predict new data to a high degree of correctness and precision.
