# CNN Image Classification

A Fashion-MNIST image-classification project using convolutional neural networks (CNNs) with TensorFlow and Keras.

## Project overview
- Dataset: Fashion-MNIST (10 clothing categories)
- Input: 28 × 28 grayscale images
- Task: Multi-class image classification
- Framework: TensorFlow / Keras

## Workflow
1. Load Fashion-MNIST training and test data.
2. Normalize pixel values and add the channel dimension.
3. Train a CNN and plot training/validation accuracy and loss.
4. Evaluate the model on the test set.
5. Explore a second model using data augmentation, convolutional blocks, batch normalization and dropout.

## Recorded results
- Initial CNN test accuracy: **91.36%**
- Improved/augmented model test accuracy: **90.50%**

These are the values recorded in the supplied notebook. The second model's recorded score is lower, so the notebook is presented as an experiment rather than claiming an improvement in test accuracy.

## Run
Open `cnn_image_classification.ipynb` in Jupyter or Google Colab and run the cells in order. Fashion-MNIST is downloaded by Keras on first use.

## Dependencies
See [requirements.txt](requirements.txt).

## Notes
The supplied notebook was reconstructed from a PDF and includes page-transcript content. Review the extracted code cells in order before treating it as a fully clean, reproducible notebook.
