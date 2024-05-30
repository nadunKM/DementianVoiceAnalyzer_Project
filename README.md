Detecting Alzheimer's Disease through speech analysis. 

## Team members:
- Butovens Médé
- Fabian Lehmann
- Nadun Dissanayake

## Overview 
This project, based on the 2021 Address Challenge, focuses on detecting Alzheimer's Disease (AD) through speech and language analysis. While memory loss is often associated with AD, changes in language patterns also provide important clinical insights. Our approach utilizes machine learning methods to identify subtle signs of AD in speech data, offering a cost-effective and scalable solution for early detection and intervention.

## Dataset description
The dataset for this project was obtained from Dementia Bank, a repository of multimedia interactions focused on studying communication in dementia. It consists of 237 recordings where participants described the cookie theft picture. The dataset includes 122 subjects diagnosed with Alzheimer's and 115 subjects from a control group.

The dataset and complete description of the challenge for the project can be found [here](https://dementia.talkbank.org/ADReSSo-2021/ "DementiaBank")

## Data processing
We used [openSMILE v2.5.0](https://pypi.org/project/opensmile/) in Python to extract features from audio files, focusing on eGeMAPS features related to frequency, amplitude, and spectral data. Feature reduction techniques were employed to address highly correlated features, resulting in a refined feature set from 88 to 37.

## Modeling
We explored several models in this project, including baseline models such as Logistic Regression, k-NN, and SVM. Additionally, we trained a Feedforward Neural Network and an LSTM model. The Feedforward Neural Network demonstrated promising results with an accuracy of 68%, precision of 69%, and recall of 72%, while the LSTM model exhibited a slightly lower accuracy of 60%, precision of 58%, and notably higher recall of 86%.

## Conclusion
The Dementia Voice Analyzer project holds significant potential to advance AD diagnosis and management by leveraging machine learning and speech analysis. Through our exploration of various models and data processing techniques, we have demonstrated promising results in early AD detection. By providing healthcare professionals with a tool that is both accurate and accessible, we aim to enhance the lives of affected individuals and families while facilitating the work of medical professionals in the field of neurodegenerative diseases.

## Next Steps
As we move forward with the Dementia Voice Analyzer project, several avenues for further improvement and development present themselves. These include:

- Incorporating linguistic features into the analysis to capture additional nuances in speech patterns related to AD.
- Refining neural network architectures to enhance model performance and robustness.
- Developing a user-friendly web application to democratize access to AD diagnostic tools and support remote assessments.
- Exploring applications beyond AD detection, such as concussion detection, to leverage the project's framework for broader impact in healthcare innovation.

## Acknowledgements
We would like to acknowledge the support of [the ERDOS institute](https://www.erdosinstitute.org/). Special thanks to Matthew Graham for their assistance with the project.