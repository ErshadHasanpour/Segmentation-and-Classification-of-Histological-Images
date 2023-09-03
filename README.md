# Segmentation and Classification of Histological Images
In this study, we employed a U-net model on histological images to classify parasite and artifact images from each other. To do this, we firstly trained a U-net model to segment those areas that are labeled as parasite or artifact. In fact, our U-net had two output channels, each of which was related to one of these categories. After training the U-net on segmentation task, we utilized it as a feature extractor to classify parasite images from artifact ones, which classification result is completely based on the aforementioned two output channels. 

![Paper1_1](https://github.com/ErshadHasanpour/Segmentation-and-Classification-of-Histological-Images/assets/96794427/0e7e1226-fe4b-4451-96d1-f807ff61f306)

Two instances of segmentation are displayed below, in the first one, which is a parasite image, only parasite channel has something to display and the artifact channel is a whole black. The same explanation is true for the second image which is an artifact image.  

![Paper1_2](https://github.com/ErshadHasanpour/Segmentation-and-Classification-of-Histological-Images/assets/96794427/d012edf6-74b3-4dbf-8e68-0f272e314d3f)

Classification results are also shown in below table.
