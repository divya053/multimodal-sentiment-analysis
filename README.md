# multimodal-sentiment-analysis

A Multimodal (Text and Images) Sentiment Analysis System using Deep Neural Networks  
The purpose of this project is to develop a comprehensive multimodal sentiment analysis system that integrates textual, visual, and auditory modalities.

The development of this multimodal sentiment analysis system holds great potential in domains such as social media monitoring, customer feedback analysis, and market research.
We used Recurrent Neural Networks (RNNs) for textual analysis, Convolutional Neural Networks (CNNs) for image analysis, and Automatic Speech Recognition (ASR) for audio analysis.

# Text-Analysis:
## Dataset:
SENTIMENT140 dataset is used for textual analysis.
It consists of a large collection of tweets from Twitter, labeled with sentiment polarity (positive or negative).
The dataset contains approximately 1.6 million tweets, making it a substantial resource for training and evaluating sentiment analysis models.
It has 6 attributes : Sentiment Polarity, Tweet ID, Date & time, Query, User, Tweet text.

## RNN:
RNNs were chosen for textual data analysis due to their ability to capture sequential dependencies and handle variable-length input sequences. This makes RNNs well-suited for analyzing sentiment in text, where the order of words and sentences is crucial for understanding the sentiment expressed.

# Audio-Analysis:
Audio Model: https://drive.google.com/file/d/1dybg6RsVxJsivnfMWi9wp8bcuC5zA8RO/view?usp=drive_link

## Dataset:
LJSpeech-1.1 dataset is used for audio analysis.
The LJSpeech-1.1 dataset is a publicly available dataset containing a large collection of English single-speaker audio clips. 
It consists of approximately 10,000 audio clips.
LJSpeech-1.1 dataset provide metadata for each audio clip, including the following information: Unique identifier, Text Transcription, Duration.

# Models Used:
For this multimodal sentiment analysis system, three different models were selected to handle the textual, image, and audio data: Recurrent Neural Networks (RNNs), Convolutional Neural Networks (CNNs), and Automatic Speech Recognition (ASR) respectively.

## RNN:
RNNs were chosen for textual data analysis due to their ability to capture sequential dependencies and handle variable-length input sequences. This makes RNNs well-suited for analyzing sentiment in text, where the order of words and sentences is crucial for understanding the sentiment expressed.

## CNN:
CNNs were selected for image data analysis. CNNs excel at extracting local and global spatial features from images, making them effective in capturing visual patterns and features that contribute to sentiment. The use of CNNs allows the system to incorporate visual information and enrich the sentiment analysis process.

## ASR:
ASR, based on a combination of 2D CNN and RNN, was employed for audio data analysis. ASR converts audio signals into textual representations, enabling the integration of auditory information into the sentiment analysis paradigm. This approach allows the system to interpret sentiments expressed through spoken words.

