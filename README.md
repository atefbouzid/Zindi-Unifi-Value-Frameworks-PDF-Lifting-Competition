# Unifi Value Frameworks PDF Lifting Competition

This repository contains the code and documentation for an AI-powered solution to extract sustainability data from annual reports. This project was developed for the Zindi Unifi Value Frameworks PDF Lifting Competition, where it achieved **2nd place in the leaderboard** and **1st place after the pitch and evaluation from the juries**.

## Project Overview

This project addresses the challenge of extracting sustainability data from annual reports. These reports often contain unstructured data and diverse document formats, making it difficult to gather and compare sustainability information efficiently. Our solution employs a combination of:

* **Natural Language Processing (NLP) techniques:** To understand the context and meaning of the text.
* **Document parsing tools:** To extract text from PDF documents.
* **Large Language Model (LLM)-based question-answering:** To extract specific data based on predefined queries.
* **Solution Overview** :
![image](https://github.com/atefbouzid/Zindi-Unifi-Value-Frameworks-PDF-Lifting-Competition/assets/122903316/d71afedf-907c-4b35-87ba-f7f9940b5055)


## Key Features

* **Robust Preprocessing Pipeline:** Removes irrelevant content, standardizes formats, and improves the quality of text for better LLM understanding.
* **Efficient Embedding and Vector Store:** Creates numerical representations of the documents for fast and accurate retrieval of relevant information.
* **Optimized LLM Interaction:** Tailored queries and prompt engineering guide the LLM to generate accurate and structured responses.
* **Data Extraction and Formatting:**  Extracts data from the LLM's responses and organizes it into a structured format for analysis.

## Results

The solution achieved promising accuracy in extracting predefined activity metrics, demonstrating the potential of this approach for automating sustainability data collection. 

**Performance Metrics (Accuracy, Precision, Recall, F1 Score)**

* Accuracy: 0.942
* Precision: 0.962
* Recall: 0.978
* F1 Score: 0.97

**Ablation Study**

The ablation study demonstrates the importance of preprocessing and LlamaParse for improved model performance:

* Round 1 (no preprocessing, no LlamaParse): Score 0.919
* Round 2 (preprocessing, no LlamaParse): Score 0.932
* Round 3 (preprocessing, LlamaParse): Score 0.947

## Files Included

* **Unifi Technical Report.pdf:** Detailed technical report outlining the project's methodology, results, and future work.
* **Presentation\_diapos.pdf:** Presentation summarizing the project's findings.
* **requirements.txt:** List of project dependencies.
* **winning\_solution.ipynb:** Jupyter notebook containing the core code for the solution.

## Getting Started

To run the code, please follow these steps:

1. Install the required packages from `requirements.txt`.
2. Download the dataset from the Zindi competition website.
3. Modify the code paths to point to your local dataset.
4. Run the Jupyter notebook to execute the solution.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## Contact

For any questions or feedback, please contact [atef.bouzid@ept.ucar.tn].

**Note:** This README.md file is a concise summary of the project. For more detailed information, please refer to the technical report.
