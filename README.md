
# MedicoBot

MedicoBot is a smart chatbot that uses AI technology to provide answers to medical questions. It is designed to offer reliable, easy-to-understand information from reputable medical sources, helping users make informed healthcare decisions.

Traditional search engines often require users to sift through vast amounts of information to find accurate answers, leading to confusion and misinformation. Our solution is MedicoPediaBot, a chatbot powered by Llama2 and trained on data from the Gale Encyclopedia. This chatbot provides concise, accurate responses to medical questions, referencing trusted sources. It can be integrated into various platforms, making medical knowledge easily accessible to users, thereby reducing the time and effort required to find reliable medical information.


## Requirements

To ensure a smooth installation of the Llama2 MedicoBot, check that your system has the following prerequisites:

- Python 3.8 or later
- pypdf
- langchain
- torch
- accelerate
- ctransformers
- sentence_transformers
- faiss_cpu
- chainlit
- huggingface_hub

## Installation

1. Clone the repository to your local system:

    ```bash
    git clone https://github.com/PragnaMargam/MedicoBot.git
    cd MedicoBot
    ```

2. Set up a Python virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. Install the necessary Python packages::

    ```bash
    pip install -r requirements.txt
    ```

4. Download the required language models and data. Refer to the Langchain documentation for detailed instructions on downloading and setting up these components.

5. Configure paths and variables in your project, such as DB_FAISS_PATH, to align with your environment.

## Setup and Launch

To launch the Llama2 Medical Bot:

- Install the required packages as outlined in the Installation section.
- Update project configurations, including setting the DB_FAISS_PATH variable.
- Prepare language models and data according to the Langchain documentation.
- Start the bot by running the provided Python script or integrating it into your application.

## Operation

To use the Llama2 Medical Bot for medical queries, follow these steps:

- Start the bot by running your application or executing the provided Python script.
- Submit a medical-related question to the bot.
- The bot will respond based on the information in its database.
- If sources are referenced, they will be included in the response.
- You can customize the bot to offer specific information depending on the query and context.