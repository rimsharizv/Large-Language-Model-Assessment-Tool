# Large Language Model Assessment Tool
Author: Rimsha Rizvi

## Description
The Large Language Model Assessment Tool is designed to systematically evaluate various large language models (LLMs) and determine their effectiveness for specific tasks. This process helps in identifying the most suitable model for a given task based on empirical data and performance metrics.

In this project, we aim to compare the performance of different large language models by querying them with a set of questions and evaluating the quality of their responses. The responses are then compared against a predefined set of correct answers to quantify the model's accuracy.

## Project Structure
The project has multiple sections, which comprise of:  
**Setup:** Initial configurations and preparations for the assessment.  
**Evaluation Set:** Construction of an evaluation set consisting of question-answer pairs.  
**Performance Measure:** Definition of evaluation metrics to measure the performance of LLMs.  
**Collecting Responses:** Querying different LLMs with question prompts from the evaluation set.  
**Analysis:** Evaluating the performance of LLMs based on their responses and reporting the results.

## Additional Explanation
The **F1 Score** is a metric used to evaluate the accuracy of the LLMs. It is the harmonic mean of precision and recall. Precision is the proportion of true positive results among all positive results, while recall is the proportion of true positive results among all the results that should have been retrieved.

In the context of this project, the F1 Score is used to quantify how well the responses from the LLMs match the correct answers. A high F1 Score indicates that the model's response is both accurate (high precision) and comprehensive (high recall), making it a reliable measure of the model's performance.
