# Image Classification using Convolutional Neural Networks (CNN) for Dogs & Cats

# OVERVIEW
This project focuses on building a CNN model to classify images of dogs and cats. The dataset used for training and testing the model is sourced from Kaggle, which contains labeled images of dogs and cats.

## Dataset
- **Dataset Link:** [Dogs vs. Cats](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- The dataset consists of images of dogs and cats, with the label '1' for dogs and '0' for cats.

## Model Architecture
- The CNN model is built using TensorFlow and Keras.
- The architecture includes convolutional layers followed by max-pooling layers for feature extraction.
- Batch normalization and dropout layers are incorporated to prevent overfitting.
- The final layer uses a sigmoid activation function for binary classification.

## Data Preprocessing
- The images are resized to a standard size of 256x256 pixels to ensure uniformity.
- Normalization is performed to scale pixel values between 0 and 1.

## Approach
### Baseline CNN Model
1. Developed a baseline CNN model using TensorFlow and Keras.
2. Trained the model on the dogs vs. cats dataset.
3. Achieved an accuracy of around 81% on the validation set.

### Transfer Learning
1. Utilized the VGG16 pre-trained model as a feature extractor.
2. Built a new model on top of the VGG16 base.
3. Fine-tuned the new model on the dogs vs. cats dataset.
4. Achieved an accuracy of around 90% on the validation set.

### Data Augmentation
1. Used data augmentation techniques to prevent overfitting.
2. Augmented the training dataset with shearing, zooming, and horizontal flipping.
3. Trained a CNN model with augmented data.
4. Achieved an accuracy of around 81% on the validation set, similar to the baseline CNN model.

## Test Results
- The model successfully classified a test image of a cat as a cat.
- The model also correctly classified a test image of a dog as a dog.

## Conclusion
This project demonstrates the effectiveness of Convolutional Neural Networks (CNNs) in classifying images of cats and dogs.
By leveraging transfer learning with the VGG16 model and data augmentation techniques, we achieved a validation accuracy of around 90%. While data augmentation did not yield significant improvements in accuracy compared to the baseline CNN model,
it played a crucial role in preventing overfitting and improving model robustness.
These results highlight the importance of pre-trained models and data augmentation for improving performance. Moving forward, further exploration of CNN architectures and deployment options could enhance the model's capabilities for real-world applications.


## Acknowledgments
The DATASET used in this analysis is sourced from [KAGGLE_DOGSVSCATS]](https://www.kaggle.com/datasets/salader/dogs-vs-cats) and is publicly available.
Picture for test of dog is taken from [Dog_Image_by_wirestock_on_Freepik](https://www.freepik.com/free-photo/selective-focus-shot-adorable-golden-retriever-outdoors_17245779.htm#fromView=search&page=1&position=18&uuid=c7ae58bb-2949-4210-b54f-b229520c6422) 
while that of cat is taken from [Image_Cat_Ralphs_Fotos](https://pixabay.com/photos/cat-kitten-feline-whiskers-pet-8121892/)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.


## Contact
For any questions or inquiries, please contact [Sayak Kumar Dutta](mailto:sayak.kr.dutta1@gmail.com).
