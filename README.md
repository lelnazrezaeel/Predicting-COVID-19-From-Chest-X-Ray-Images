# Predicting-COVID-19-From-Chest-X-Ray-Images
Welcome to the "Predicting COVID-19 From Chest X-Ray Images" project. This project aims to implement the code described in [Article Number 1](https://paperswithcode.com/paper/deep-covid-predicting-covid-19-from-chest-x) and extends its capabilities using the findings from [Article Number 2](https://www.frontiersin.org/articles/10.3389/fmed.2021.629134/full). The authors of Article Number 1 applied Transfer Learning on four different architectures to detect COVID-19 and classify chest X-ray images. In this project, we build upon the results presented in Article Number 2 by incorporating additional data from [this dataset](https://www.dropbox.com/s/9w8nmj791c9ogsx/data_upload_v3.zip) into the dataset of Article Number 1. Finally, we apply Transfer Learning on two specific architectures, Squeeznet and ResNet-18.

## <img width="25" height="25" src="https://img.icons8.com/dotty/80/41b883/overview-pages-2.png" alt="overview-pages-2"/> Overview
The project can be divided into the following key components:

### Data Integration

We enhance the dataset used in Article Number 1 by incorporating additional data from [this dataset](https://www.dropbox.com/s/9w8nmj791c9ogsx/data_upload_v3.zip). This expanded dataset will be used for training and evaluation.

### Model Architecture

We focus on one specific model architectures:

#### ResNet-18

For the ResNet-18 model, we train only the last layer (Fully Connected) and the last sequential layer. This transfer learning approach allows us to leverage the pre-trained ResNet-18 model's features while adapting it to our specific task.
