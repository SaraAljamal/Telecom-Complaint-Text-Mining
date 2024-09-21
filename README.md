# Telecom-Complaint-Text-Mining
A text mining project analyzing telecommunication company complaints in both Arabic and English. The project involves preprocessing text data, finding the most relevant complaints based on user input, and generating graphical insights.


_**Problem Statement**_

In this project, we aim to assist a telecommunication company in efficiently handling customer complaints by utilizing text mining techniques.The objective is to:
- Preprocess the text data.
- Find the most relevant complaints based on a user’s input (employee).
- Visualize the results using relevant graphs to provide insights into complaint patterns.
This solution will improve customer support by enabling employees to quickly access similar complaints, helping them address issues faster and more effectively.

_**Dataset**_

The dataset consists of customer complaints in both Arabic and English languages from a telecommunication company.

_**Project Workflow**_
1. Data Preprocessing:
   - Text Cleaning: Removing stop words, punctuation, and normalizing text for both Arabic and English complaints.
   - Tokenization: Breaking down the text into individual words or phrases.
   - TF-IDF: Applied Term Frequency-Inverse Document Frequency (TF-IDF) to convert textual data into numerical form.
     
2. Relevance Matching:
   - Implemented a similarity search technique (e.g., Cosine Similarity) to find the most relevant complaints based on a user's query.
   - The system retrieves and ranks the top complaints related to the query entered by the user (employee).

3. Graph Data Mining:
 - Prefix and Suffix Connections Graph: A graph was created to demonstrate how words in the query connect based on prefixes and suffixes. Centrality measures were calculated to determine the importance of each word in the graph.
 - Co-occurrence Graph: Developed a graph showing the co-occurrence of words in at least five complaints. The edges of the graph represent the number of times two words co-occurred, with the weights indicating the strength of their relationship.
 
4. Graphical User Interface (GUI):
- A simple, user-friendly graphical interface was created to allow employees to interact with the system. Through the GUI, employees can enter their query and retrieve relevant complaints and graphs.

_**Tech Stack**_
- Python: For data processing and text mining.
- Pandas: For data manipulation and numerical operations.
- NLTK: For text preprocessing and natural language processing (NLP).
- Arabic Text Libraries: pyarabic, arabic_reshaper, and bidi for handling Arabic text preprocessing and visualization.
- Scikit-learn: For applying TF-IDF and cosine similarity.
- NetworkX: For graph creation and analysis.
- Tkinter: For building the GUI.
- Matplotlib: For visualizing the graphs.
- Jupyter Notebook: For code execution and experimentation.

_**How to Use**_
1.	Jupyter Notebooks:
-	Notebook 1: Preprocessing and Full Text Mining (Complaint_Text_Mining.ipynb):
This notebook covers all the steps from preprocessing the complaints data, text mining, calculating TF-IDF, and finding the most relevant complaints using cosine similarity. It also includes the graph creation for word connections and co-occurrences, but without the graphical user interface (GUI).
      -	Run this notebook to view the complete workflow and text mining process.

-	Notebook 2: GUI Creation (Complaint_Text_Mining_GUI.ipynb):
This notebook focuses on building the graphical user interface (GUI) that allows employees to input queries, retrieve relevant complaints, and display the two graphs (word connection graph and co-occurrence graph). The preprocessing steps are already assumed to be done.
      -	Run this notebook to interact with the GUI and test the system functionality.
        
2.	Presentation:
-	The presentation (Complaint Text Mining Presentation.pptx) provides a high-level overview of the project, including the theoretical background of data mining, text mining, and graph mining techniques.
-	You can download or view the presentation to understand the project context and results.

