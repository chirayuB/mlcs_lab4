# mlcs_lab4

Outline:
This code repository comprises the implementation of an innovative system designed to detect hidden vulnerabilities, commonly referred to as backdoors, in neural networks. The main goal of this project is to bolster the security of neural networks, specifically those trained on the YouTube Face dataset. This is accomplished by creating an advanced model called GoodNet, intricately crafted to differentiate between regular and compromised inputs, effectively categorizing them into distinct classes.

System Specifications:
Macbook M1 with the Google Collab Pro interface. Please make sure to use Collab Pro as this project requires higher RAM than what the basic Collab has to offer.

Repository Structure:
Notebook report Model: model_x_10.h5 , model_x_2.h5 , model_x_4.h5

Installation and Operation Guide
Downlaod the repo to your system, connect to Google drive and use it on Google Collab Pro.

Data:
1)Download the validation and test datasets from here and upload them to Google Drive under bd/ and cl/ and sunglasses_bd_net.h5

2)The dataset contains images from the YouTube Aligned Face Dataset. We retrieved 1283 individuals and split them into validation and test datasets.

3)bd_valid.h5 and bd_test.h5 contains validation and test images with sunglasses trigger respectively, that activates the backdoor for bd_net.h5.# ml_cybersec_lab4
