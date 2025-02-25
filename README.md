# Project Name
Melanoma Cancer Detection



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Skin cancer ISIC The International Skin Imaging Collaboration dataset has been used here

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1
  Training & Validation Accuracy Trends The training accuracy improves steadily from 22.87% (epoch 1) to 89.15% (epoch 20). The validation accuracy also increases from 36.91% to 89.93%. The two accuracy curves remain close to each other, which is a good sign—indicating that the model is generalizing well.

Training & Validation Loss Trends The training loss decreases from 2.11 to 0.27, showing that the model is learning. The validation loss also drops from 1.79 to 0.25. The validation loss does not increase sharply at the end, which suggests that the model is not overfitting significantly.

Checking for Overfitting Overfitting occurs when the training accuracy is very high, but validation accuracy stops improving or starts decreasing. Here, training and validation accuracy remain close throughout, which means no strong overfitting is present. However, by epoch 17-20, training accuracy is higher than validation accuracy (89.15% vs. 89.93%), so mild overfitting might be starting.

Checking for Underfitting Underfitting happens when both training and validation accuracy remain low or the model fails to learn patterns. Since accuracy improves significantly over time (from ~20% to ~90%), there is no sign of underfitting.

Even though the model is performing well, some fine-tuning can help: Data Augmentation – Helps improve generalization & reduce overfitting Regularization (Dropout, L2 Regularization) – Can prevent overfitting in later epochs
- Conclusion 2
  No significant overfitting observed: Training and validation accuracy are close to each other throughout the epochs. Validation accuracy surpasses training accuracy in later epochs, which is not typical of overfitting. This could indicate that the model learns better representations or that regularization is effective. Loss curves are decreasing steadily for both training and validation, which is a good sign.

Yes, the validation accuracy has improved compared to the previous model run. The training and validation loss curves are more aligned, suggesting the Dropout layer helped in reducing overfitting.
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
