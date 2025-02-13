# Information Retrieval on image dataset

This is a repository consisting of the code required to both label an image dataset thanks to AI and 
then to search through this dataset through prompts.

## How to Use

1. Get the Gemini api key

2. Create a .env file

3. Put this in your .env file

API_KEY=your_api_key

4. Do the steps bellow and it'll work

python3 -m venv InformationRetrievalEnv

source InformationRetrievalEnv/bin/activate

pip install -r requirements.txt

python3 gemini_api.py

