# Big Data-powered Vietnamese Hate Speech Detection: A Kafka - Deep Learning Approach

## Abstract

In this research, we have developed a Kafka-based system aimed at detecting hate speech within live videos streamed on the YouTube platform. The system comprises two main components: offline and online. In the offline component, we conducted experiments with various Machine Learning and Deep Learning models, utilizing two datasets to determine the most effective model for hate speech detection task. Moving on to the online component, comments from the chat box of live YouTube videos are systematically crawled, and the model predicts whether each comment should be classified as hate speech or clean. Subsequently, we label and evaluate these comments to enhance the model's performance, particularly when it encounters misclassifications. This two-fold approach ensures a robust and adaptive system for the real-time detection of hate speech in the dynamic environment of live video streams on YouTube.

## Usage

The project comprises two code files: "Youtube_Live_Chat" and "Kafka_Deep_Learning." The "Youtube_Live_Chat" file is designed to collect real-time comments from a specified live stream video on YouTube. These comments are then stored in CSV files, with each file containing 10 comments.

On the other hand, the "Kafka_Deep_Learning" file serves the purpose of establishing a comprehensive pipeline that encompasses the entire process, starting from loading data from CSV files to making predictions. The pipeline involves various steps, such as loading the CSV files, preprocessing the data, writing to Kafka topics, and utilizing Kafka to stream the data for predictive modeling. The code in the final cell of the file constitutes a complete pipeline, initialized in a loop. This loop ensures that whenever a new CSV file is detected, the pipeline automatically executes the aforementioned steps.

## System Architecture

<img width="500" alt="image" src="https://github.com/motcapbovit/Big-Data-powered-Vietnamese-Hate-Speech-Detection-A-Kafka-Deep-Learning-Approach/assets/72774923/34ce6acd-ac3b-4505-802b-8f7e7b077450">

## Model Evaluation

<img width="500" alt="image" src="https://github.com/motcapbovit/Big-Data-powered-Vietnamese-Hate-Speech-Detection-A-Kafka-Deep-Learning-Approach/assets/72774923/e3944f38-9dec-4f5b-89a6-7bbf5dcdb5d4">

## Contact
[Chi Thanh Dang](https://github.com/motcapbovit), [Thuy Hong Thi Dang](https://github.com/KaytlynDangDS) and Van Nguyen Dinh

Faculty of Information Science and Engineering, University of Information Technology, Vietnam National University, Ho Chi Minh City, Vietnam.

20520761@gm.uit.edu.vn, 20520523@gm.uit.edu.vn, 20520657@gm.uit.edu.vn
