Project 1: Zero-Shot & Few-Shot Data Extraction

Objective

The objective of this project is to extract structured information from unstructured text using Prompt Engineering techniques and return the output in JSON format.

Concepts Used

* Zero-Shot Prompting
* Few-Shot Prompting
* Delimiters
* JSON Formatting
* Hallucination Reduction

Problem Statement

Large Language Models often receive messy and unstructured text. The goal of this project is to design prompts that accurately extract specific information and return clean JSON output.

Prompt Design

The prompt instructs the model to:

* Extract Name
* Extract Email
* Extract Phone Number
* Return only valid JSON
* Avoid conversational text

Sample Input

My name is Ali Khan.

Email: ali@gmail.com

Phone: 03001234567

Sample Output

{
“name”: “Ali Khan”,
“email”: “ali@gmail.com”,
“phone”: “03001234567”
}

Testing

Multiple test cases were executed using different input formats to verify extraction accuracy.

Results

The model successfully converted unstructured text into structured JSON output.

Learnings

* Importance of prompt clarity
* Zero-Shot vs Few-Shot prompting
* Structured data generation
* Reliable JSON formatting

Conclusion

This project demonstrated how Prompt Engineering can be used to transform raw text into structured machine-readable data.
