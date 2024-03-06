# Pneumonia Detection from Chest X-Ray Images
## Pneumonia

Pneumonia is an infectious respiratory condition characterized by inflammation of the air sacs (alveoli) in one or both lungs. It can be caused by various organisms, including bacteria, viruses, fungi, and parasites. Pneumonia can range in seriousness from mild to life-threatening and is most serious for infants and young children, people older than age 65, and people with health problems or weakened immune systems.

## Dataset

We are tilizing a dataset provided by [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) The dataset comprises 5,856 JPEG images categorized into two groups: Pneumonia and Normal, distributed across train, test, and validation folders.

![image](https://github.com/CharuNish/Pneumonia-Detection/assets/60501756/9db8c539-c12c-42b7-8dea-41da0affbd1c)


## Model

We have utilized a fine-tuning approach on an EfficientNet model, a cutting-edge convolutional neural network architecture known for its efficiency and accuracy in handling image classification tasks. By adjusting the final layers of the pre-trained EfficientNet to suit our binary classification task, we managed to achieve significant accuracy in detecting pneumonia from chest X-ray images.

## Results

The model demonstrated promising results, achieving an accuracy of **87%** on the test set with 20 epochs, 16 batch size and 0.01 learning rate.

