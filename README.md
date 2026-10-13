# EXP-5
# Experiment 5: Zero-Shot vs Few-Shot Prompting for Sentiment Analysis

## Aim
To compare zero-shot and few-shot prompting techniques for sentiment classification using the Gemini API.

## Objective
Classify customer reviews into positive, negative, or neutral sentiments and compare the accuracy of both prompting techniques.

## Technologies Used
- Python
- Google Gemini API
- Google Gen AI SDK
- Pandas

## Dataset
The experiment uses five phone reviews with predefined actual sentiment labels.

## Methodology
1. Prepare the customer reviews and actual sentiment labels.
2. Classify each review using zero-shot prompting.
3. Classify each review using few-shot prompting with examples.
4. Compare predicted labels against actual labels.
5. Calculate and compare the accuracy of both methods.

## Results
The program prints the predictions, accuracy counts out of five, and the final comparison conclusion.

## How to Run
1. Install the required libraries using `pip install -r requirements.txt`.
2. Configure your Gemini API key securely.
3. Run `python experiment5.py`.

## Note
A valid Gemini API key and an available Gemini model are required. API quotas may apply.
