# Historical Document Analysis

This project leverages Large Language Models and natural language processing (NLP) techniques to analyze and extract valuable insights from historical apprenticeship agreements. By automating the extraction of structured data from unstructured text, this project aims to uncover patterns, trends, and key information that would be difficult to obtain manually.

🚀 **Project Overview**

This project focuses on analyzing historical documents, specifically apprenticeship agreements, using a combination of data processing, machine learning, and NLP. The goal is to extract structured information such as the names of officials, mentors, apprentices, their ages, states, and counties, and to provide insights into the historical context of these agreements.

**Key Features:**

* **Data Cleaning and Preprocessing:** Automatically cleans and prepares historical text data for analysis.
* **Machine Learning Integration:** Utilizes OpenAI's GPT-3.5 and LLaMA models for text analysis and information extraction.
* **Structured Data Extraction:** Converts unstructured text into structured JSON format for easy analysis.
* **Document Similarity Detection:** Determines if two pages belong to the same document by comparing names, places, and dates.
* **Data Aggregation and Visualization:** Aggregates data from multiple pages and provides visual insights into the dataset.

📂 **Project Structure**

The project is organized as follows:

**Notebooks:**

* `History_LLM.ipynb`: The main Jupyter notebook containing the code for data loading, cleaning, machine learning, and analysis.

**Data:**

* `contract-records.csv`: The dataset containing historical contract records, including apprenticeship agreements.
* `task2-apprenticeship-agreements-sample.csv`: A sample dataset for testing and development.
* `task3-merged-apprenticeship-agreements.csv`: A dataset containing merged apprenticeship agreements.
* `task4-parsed-apprenticeship-agreements.csv`: A dataset containing parsed apprenticeship agreements with extracted JSON information.

**Libraries:**

* `pandas`: For data manipulation and analysis.
* `openai`: For accessing GPT-3.5 for text analysis.
* `ollama`: For using LLaMA models for NLP tasks.
* `replicate`: For running machine learning models.
* `langchain`: For integrating language models and creating chains of NLP tasks.

🛠️ **How It Works**

**Data Loading and Cleaning:**

* The project starts by loading the historical contract records from a CSV file.
* It cleans the text data by removing unwanted characters and filtering relevant entries.

**Machine Learning and NLP:**

* The project uses OpenAI's GPT-3.5 and LLaMA models to process and analyze the text data.
* It sets up a system to determine if two pages of a document are from the same document by checking for similar names, places, and dates.

**Structured Data Extraction:**

* The project extracts specific information from the text, such as the names of officials, mentors, apprentices, and their ages, states, and counties.
* This information is formatted into JSON for easy analysis.

**Data Aggregation and Analysis:**

* The project aggregates text from multiple pages of the same document and processes it to extract structured information.
* It calculates the average age of apprentices and counts the occurrences of different ages in the dataset.

**Visualization and Reporting:**

* The project includes basic visualization, such as plotting the distribution of apprentice ages.
* It generates a final DataFrame containing the aggregated text and the extracted JSON information.

📊 **Key Insights**

* **Socioeconomic Mobility Indicators:** Beyond simple age averages, the system can identify potential socioeconomic mobility patterns by correlating apprentice ages with mentor locations and official involvement. This reveals insights into the accessibility of apprenticeships across different regions and social strata.
* **Geographical Distribution of Trades:** The project analyzes the geographic distribution of apprenticeship agreements, identifying regions with concentrations of specific trades. This allows for a deeper understanding of regional economic specializations and the historical evolution of skilled labor.
* **Temporal Trends in Apprenticeship Practices:** By examining the chronological distribution of agreements, the system can uncover changes in apprenticeship practices over time, such as shifts in age demographics, contract durations, and the involvement of local authorities.
* **Network Analysis of Key Individuals:** The project can create network graphs connecting officials, mentors, and apprentices, revealing influential figures and the structure of local apprenticeship networks. This provides a nuanced view of the social fabric surrounding historical training and labor practices.
* **Comparative Analysis of Textual Variations:** Through NLP techniques, the project can identify and analyze variations in the language used in apprenticeship agreements across different regions or time periods, highlighting potential regional legal differences or evolving social norms.

🚀 **Getting Started**

**Prerequisites**

* Python 3.x
* Jupyter Notebook
* Required Python libraries: `pandas`, `openai`, `ollama`, `replicate`, `langchain`

**Installation**

1.  Clone the repository:

    ```bash
    git clone [https://github.com/yourusername/historical-document-analysis.git](https://www.google.com/search?q=https://github.com/yourusername/historical-document-analysis.git)
    cd historical-document-analysis
    ```

2.  Install the required libraries:

    ```bash
    pip install pandas openai ollama replicate langchain
    ```

3.  Open the Jupyter notebook:

    ```bash
    jupyter notebook History_LLM.ipynb
    ```

4.  Follow the instructions in the notebook to load the data, run the analysis, and visualize the results.

🤝 **Contributing**

We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bugfix.
3.  Commit your changes.
4.  Submit a pull request.

📜 **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

