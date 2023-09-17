# Document Summarizer
This project is a document summarizer that uses the OpenAI API. The system can summarize the content of multiple documents and save the summaries to JSON files.
## Scripts
- `doc_summarize.py`: The main script that orchestrates the whole process. It reads the content of several text files from the `data` directory, each file representing a document. It splits each document into chunks and sends each chunk to the OpenAI API for summarization. It groups the summarized chunks by document and saves the summaries to a JSON file named `summaries.json`. It then summarizes each summary again and saves the final summaries to a JSON file named `final_summaries.json`.
## Directories
- `data`: Contains several text files. Each file name suggests a topic related to artificial intelligence, machine learning, and data science. These files likely contain data or information related to their respective topics.
## Dependencies
The Python packages that the project depends on are listed in the `requirements.txt` file.
