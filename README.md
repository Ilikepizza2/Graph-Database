# Knowledge Graph Construction and Exploration with Rebel and Gemini
### [Link to colab notebook](https://colab.research.google.com/drive/1VqDbCCaUuNtWBxmTBOz7lotii17BFwS4?usp=sharing)
This project demonstrates building and exploring knowledge graphs (KGs) using either of the two models: Rebel(seq2seq) and Gemini(Google LLM). 

## Functionalities

* **KG Construction:** Build KGs using either:
    * **Provided Text:** Define your own text for analysis.
    * **Gemini-Generated Text:** Let Gemini generate text for KG construction.
* **Model Selection:** Choose between Rebel and Gemini for relation extraction.
* **Querying:** Perform various KG queries:
    * Keyword search
    * Semantic BFS (breadth-first search)
    * Semantic document search based on embeddings
* **Visualization:** Convert the KG to a network graph for visual exploration (requires `pyvis` library).

## Running the Project

1. **Access the Colab Notebook:** [Link to your Colab notebook here]
2. **Install Libraries:** Follow the instructions in the notebook to install required libraries (e.g., `rebel-api`, `pyvis`).
3. **Obtain API Keys:** If using Rebel, acquire an API key from https://huggingface.co/Babelscape/rebel-large and set the `REBEL_API_KEY` environment variable in Colab. For Gemini, obtain your gemini api key and set the `GOOGLE_API_KEY`.
4. **Run Cells:** Execute the notebook cells to construct, query, and visualize your KG.

## Additional Notes

* Refer to the notebook for detailed explanations and customization options.
* Experiment with different text inputs, models, and query types to explore your data.
* Consider installing `pyvis` locally for offline visualization.

This project provides a starting point for building and interacting with KGs using LLMs in Google Colab. Feel free to adapt and extend it for your specific needs.
