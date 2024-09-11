# 102115217_sess_le1 
# REPORT
## About the research paper
The Speech Commands dataset is an open-source resource designed for developing and assessing keyword spotting systems. Its primary aim is to facilitate the creation and evaluation of small models that identify specific spoken words from a set of ten or fewer target words, while minimizing false positives from background noise or unrelated speech. This dataset standardizes model comparisons, fostering advancements in the field and promoting collaborative progress.

Key Findings
Standardization: The dataset allows for standardized comparisons between keyword spotting models, which is crucial for advancing the field.
Model Comparison: It enables meaningful evaluations of different models' performance in distinguishing between speech-containing audio and non-speech clips.
Accuracy Improvement: The Version 2 dataset demonstrates improved accuracy with a Top-One score of 88.2% on the training set and 89.7% on the Version 1 test set.
Specialization: While other datasets like Mozilla’s Common Voice support general speech tasks, they are not tailored for keyword spotting. The Speech Commands dataset specifically addresses the need for testing and building on-device models, providing comparable metrics and reproducibility for baseline models.
Utility: The dataset is valuable for training and assessing various models, with Version 2 showing enhanced performance on comparable test data relative to the original.
The dataset was gathered using an open-source, web-based application utilizing the Web Audio API. This user-friendly application aimed to reduce completion failures by recording short utterances of words from a predefined list. Each recording was processed to eliminate quiet or silent segments and to extract the loudest part of the clip. The default convolution model from the TensorFlow tutorial was trained using both Version 1 and Version 2 data, and the models were evaluated against the corresponding test sets.

In conclusion, the Speech Commands dataset serves as a benchmark for evaluating keyword spotting performance, with Version 2 showing significant improvements over the original dataset. It remains an effective tool for training and assessing various models in keyword spotting.
# Activities Completed
## Recording Audio Samples:

Recorded 30 audio samples, each containing 35 distinct words.
Used a laptop voice recorder for capturing the audio.
## Dataset Preparation:
Compiled the recorded audio samples into a zip archive.
Uploaded the zip file to the working environment.
Extracted the zip file to access the individual audio files for processing.
## Data Extraction:
Extracted the dataset from the zip file to a specified directory.
Ensured the audio files were ready for model training by organizing and processing them.
## CNN Model Classifier Development:
Selected and implemented a Convolutional Neural Network (CNN) model for the keyword spotting task.
Configured the CNN model to work with the extracted audio dataset.
## Dataset Splitting:
Prepared the dataset for training and testing.
Planned to split the dataset into training and testing subsets to evaluate the model’s performance.
## Fine-Tuning Process:
Initiated the fine-tuning of the CNN model using the prepared dataset.
Applied training data to optimize the model for keyword detection.
## Evaluation:
Evaluated the model’s performance based on the dataset’s results.
Addressed initial challenges related to dataset quality and model configuration.
## Challenges Encountered:
Faced limitations due to lack of GPU resources, affecting the ability to complete and optimize the model training process.
Unable to fully fine-tune the model and apply necessary corrections due to computational and time constraints.
# Snapshots
![image](https://github.com/user-attachments/assets/ac0a433e-9967-4820-8ec1-f720097d7e23)
![image](https://github.com/user-attachments/assets/0001f2f9-e3dc-448c-b446-ff7ed60d21c0)
![image](https://github.com/user-attachments/assets/04eb4750-c1b7-4cc3-9054-46bbe9e7cd81)
# Colab Notebook
In the repo itself also link
# Self Created Database:
https://drive.google.com/drive/folders/1IVhDIb2ny4mcmF6QOg1L537NeGAE5GxW?usp=sharing
