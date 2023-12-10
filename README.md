# Clone the repository
`git clone https://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@github.com/swayambhu2104/Retriever.git`

# Change directory 
`cd Retriever`

# Install package
`pip install -r requirements.txt`

# Run the following command to retrieve the necessary tools
To ask custom query write your custom query within quotes in the --query field
```
export PYTHONPATH=./
python llama_index_retriever.py \
--query "Find all work items created by users DEVU-123 and DEVU-456 and summarize them." \
--api_key {insert your openai api key}
```
