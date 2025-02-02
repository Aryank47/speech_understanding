# Speech Understanding Course Assignment 1

This repository contains the solutions for the Speech Understanding course assignment 1.

## Assignment Details

### Question 1 (Group Assignment)

In a group of two students, you are required to perform a detailed analysis of a task related to speech processing. Examples of relevant tasks include:

- Speech recognition
- Speaker identification
- Emotion recognition
- Speech synthesis
- Accent detection
- Any other related task

Your analysis should address the following:

- **Task Explanation:** Describe the task and its real-world importance.
- **SOTA Models Analysis:** Compare and briefly describe the state-of-the-art (SOTA) models or tools available for the task. Discuss their strengths and limitations.
- **Evaluation Metrics:** Analyze the results using appropriate metrics (e.g., accuracy, precision, recall, F1-score) and explain the strengths and limitations of each metric.
- **Open Problems and Opportunities:** Identify the open problems and potential opportunities related to the task.

The submission should include a detailed report, a short presentation, and all codes/datasets used.

### Question 2 (Individual Assignment)

This question focuses on experimenting with spectrograms and windowing techniques using the UrbanSound8K dataset.

#### Task A:

1. **Dataset:** Use the UrbanSound8K dataset.
2. **Windowing Techniques:** Implement the following windowing techniques:
   - Hann Window
   - Hamming Window
   - Rectangular Window
3. **Spectrogram Generation:** Write a Python program that applies these windowing techniques to generate spectrograms using the Short-Time Fourier Transform (STFT). Compare the spectrograms visually and analyze the differences. Discuss how each windowing technique affects the spectrogram quality and the correctness of the windowing performed.
4. **Classifier Training:** Train a simple classifier (e.g., SVM or neural network) using features extracted from the spectrograms. Evaluate and compare the performance of the different techniques. The report should include a detailed comparative analysis of the results.

#### Task B:

Select 4 songs from 4 different genres and compare their spectrograms. Provide a detailed comparative analysis based on your observations and insights from speech understanding.

The submission for Question 2 must include the code, the songs used for analysis, and the report.

## Getting Started

### Dataset

Download the UrbanSound8K dataset from Kaggle:  
[UrbanSound8K Dataset](https://www.kaggle.com/datasets/chrisfilo/urbansound8k)

### Installation

Make sure to install the following Python packages:

- `torch`
- `librosa`
- `matplotlib`
- `sklearn`
- `seaborn`

### Running the Code

- **Task A:** Navigate to the folder `question2_taskA` and run `taskA.ipynb`.
- Ensure that the UrbanSound8K dataset is stored in the correct folder as required by the code.
