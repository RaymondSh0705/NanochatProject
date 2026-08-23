# NanochatProject
Creating full training loop and inference loop of a mini-parameter LLM chatbot. Uses transformer, rotary embeddings, and KV caching.

# Usage

#### Organization
- Cells are organized into sections (i.e., Create Tokenizer, Train Our Model, etc)
- Cells that should only be run once are labelled in the heading
- Run cells in sequential order
- When running the training/inference loop, the code will save/check for model weight checkpoints saved onto the local machine (code automatically creates such files)

#### Installation
```
pip install -r requirements.txt
```
#### Inference Loop
To use the inference loop, you must create a Hugging Face account and generate an API token.
- Set the environment variable locally before running the scripts
```
export WANDB_API_KEY="your_key_here"`
```
