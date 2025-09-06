# Medical_chatbot
end to end medical chatbot using langchain, RAG, Gemini and Flask


# How to run?
### STEPS:
Clone the repository

```bash


### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & google credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```

### Techstack Used:

- Python
- LangChain
- Flask
- Gemini
- Pinecone

### Outputs:
<img width="1919" height="1079" alt="Screenshot 2025-09-06 112939" src="https://github.com/user-attachments/assets/58623fc8-a7d9-47e0-823e-fc3a5f76212c" />


<img width="1890" height="1079" alt="Screenshot 2025-09-06 113022" src="https://github.com/user-attachments/assets/3923366e-208e-45f8-91ae-d04fc5df30b5" />
