Project 3: Context-Anchored Answering (RAG Basics)

Objective

The objective of this project is to prevent hallucinations by forcing the model to answer only from the provided reference text.

Concepts Used

* Retrieval-Augmented Generation (RAG)
* Context Injection
* Negative Constraints
* Closed-Book Answering
* Citations

Problem Statement

Large Language Models may generate incorrect information when answering questions. This project focuses on grounding answers in a provided document and preventing unsupported responses.

Prompt Design

The prompt instructs the model to:

* Use only the provided context
* Ignore external knowledge
* Provide citations
* Return “Information Not Found” when the answer is missing

Reference Text

Ali lives in Lahore.

Ali is 25 years old.

Sample Question

Where does Ali live?

Sample Answer

Lahore

Source: Paragraph 1

Missing Information Example

Question:

What is Ali’s salary?

Answer:

Information Not Found

Testing

Multiple questions were tested against the reference document to verify factual accuracy.

Results

The model successfully answered questions from the provided context while avoiding hallucinations.

Learnings

* Context grounding
* RAG fundamentals
* Citation-based answering
* Safe AI responses

Conclusion

This project demonstrated how context injection and negative constraints improve the reliability and factual accuracy of AI-generated answers.
