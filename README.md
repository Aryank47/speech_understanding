This repo consists of the solution for the speech understanding course assignment 1:
the assignmet details are as follows:

Question 1: In a group of two students, you have to perform a detailed analysis of one task
related to speech processing (examples include speech recognition, speaker identification,
emotion recognition, speech synthesis, accent detection, or any other relevant task). Perform a
detailed analysis covering the following aspects: Prepare a detailed report and a short
presentation by comparing and briefly describing the SOTA models available for each task.
These should include the following:

- Explain the task and its importance in the real world.
- Analyze the strengths and limitations of state of the art models or tools in terms of the
  methods or models available.
- Discuss the results in terms of the metrics used to evaluate the task, including their
  strengths and limitations.
- Suggest what are the open problems and opportunities corresponding to that problem
  statement.
- Submission should include the presentation, report and the codes/datasets you have
  worked with for this question.

Question 2: This question is to be submitted individually. Experimenting with Spectrograms
and Windowing Techniques.
Task A.

1. Use the UrbanSound8k dataset for this assignment.

2. Understand and implement the following windowing techniques:
   a. Hann Window
   b. Hamming Window
   c. Rectangular Window
3. Write a Python program to apply the above windowing techniques → Generate
   spectrograms using the Short-Time Fourier Transform (STFT)
   (Compare the spectrograms visually and analyze their differences. Discuss the
   correctness of windowing performed.)
4. Train a simple classifier (e.g., SVM or neural network) using features extracted from the
   spectrograms and evaluate the performance results comparatively in different
   techniques.
   In Report write the comparison and analysis of the results computed.

Task B.
Select 4 songs from 4 different genres and compare their spectrograms. Analyze the
spectrograms and provide a detailed comparative analysis based on your observations
and speech understanding.
Submission for both the tasks includes codes, songs you have used for analysis, and the report.

To run this code first download the data sets:
UrbanSound8k: https://www.kaggle.com/datasets/chrisfilo/urbansound8k

Install the following packages:
torch librosa matplotlib sklearn seaborn

To run a .ipynb go
