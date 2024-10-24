
# Task 1: Fine-tuning TTS for English with a Focus on Technical Vocabulary


## Dataset Description

The dataset used for training and evaluation was "Yassmen/TTS_English_Technical_data", which contains approximately 9,951 audio samples and corresponding transcriptions of English technical content.  The dataset was preprocessed to normalize the text by converting it to lowercase, removing punctuation, and removing extra whitespace.

[![Hugging Face Datasets](https://img.shields.io/badge/Hugging%20Face%20Datasets-464646?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/datasets/Yassmen/TTS_English_Technical_data)


## Dataset Creation 

A custom dataset comprising 6,000 audio samples with corresponding English transcriptions of technical content has been created. However, due to resource limitations, this dataset could not be utilized for the current experiment.

The scale of the dataset might be a contributing factor to the limitations. 6,000 samples, while substantial, might not provide the breadth and depth required to capture the intricacies of technical English and its specific pronunciation patterns.

Additionally, the computational demands of training a robust speech model on a dataset of this size could exceed the available resources.

[![Hugging Face Datasets](https://img.shields.io/badge/Hugging%20Face%20Datasets-464646?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/datasets/Shabdobhedi/TTS_English_Technical_Terms)

## Dataset Creation Notebook 

[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/code/manaspkundu/dataset-english-techn)



## Training Logs



The model's performance improved over time, as shown in the training logs. The training loss decreased gradually, indicating that the model learned to generate speech that closely matched the normalized text. The validation loss also decreased, suggesting that the model generalized well to unseen data.

## Evaluation Results

 The decreasing validation loss suggests that the model's performance on unseen data improved during training. 

## The Technical Terms List  

text = "The developer utilized the CUDA API to accelerate the training of the TTS model while the REST API with OAuth 2.0 was employed for secure access and authentication."


## Their correct pronunciation output from the fine-tuned model

[![Listen on Google Drive](https://img.shields.io/badge/Listen%20on-Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1bqyIJOWXW5ZHbwJa30PF36LqXzqixAc9/view?usp=sharing)

## Note

I am so sorry i am not able to do this Task

Use both objective metrics such as Mean Opinion Score (MOS) and subjective evaluations from native English speakers familiar with technical terms. You may also want to consider pronunciation accuracy (e.g., comparing phoneme representations).


