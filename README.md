# ChestXRCovid19

AUTHOR: Hassan NEHME
DATE: 1 APRIL 2022

<p style='text-align: justify; font-size:15px '>COVID-19 is a respiratory disease caused by severe acute respiratory syndrome coronavirus (SARS-CoV-2). The disease has caused tremendous pressure on healthcare systems and resources due to its rapid spread across the world.  Early diagnosis and isolation of patients has proven essential in slowing down the virus’s spread. Although the actual leader diagnosis test is the Reverse transcription Polymerase chain reaction (RT-PCR), it has some limitations such as being time-consuming, expensive, inaccessible in some countries and having low-sensitivity; hence, other fast and accessible diagnostic tools are needed. Inspired by recent research that correlates the presence of COVID-19 to findings in chest X-ray images we design, examine and compare different deep learning (DL) models to process and classify images into three different classes: Normal, Pneumonia and COVID-19. Starting with our proposed CNN model we extend to two different wel known DL approaches (ResNET-50 and Xception) based on standard benchmarks which are studied and evaluated in details. The proposed systems involve a pre-processing stage with image augmentation, enhancement, normalisation and resizing of CXR images. After this stage comes the classification model trained under different schemes; and finally, the result analysis and interpretation. Accuracy, precision, recall and F-1 score are used as metrics to access the quality and performance of the proposed models. Each model will be built using the <b>Keras API</b> provided by <b>Tensorflow</b>. Some of the models have been implemented in a <b>Google Colab environement</b> which offers the Tesla K80 GPU, and the others have been implemented locally with an Apple M1 Metal GPU. </p>

# What is in here?

1 In the notebook.ipynb you find the code for all the implemented models alongside the obtained results after complete training and validation.
  Note that it took around half a day to train each one of these models.
  
2 In the models folder you can find all the saved models, one per directory.

3 The original files are available on this address: [to_kaggle](https://cxr-covid19.grand-challenge.org/). 

