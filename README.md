# Fine Tuning Pegasus for Text Summarization 

This repository contains a FastApi application for an enhanced Q&A bot that leverages Pegasus model and FastApi. The app allows users to interact with the Model and get responses based on their queries.

## DataSet

- SAMSum dataset contains about 16k messenger-like conversations with summaries
- Data Splits
- train: 14738
- test: 819

## Pegasus Model

- The Pegasus model, developed by Google Research, is a large and sophisticated transformer-based model designed specifically for abstractive text summarization.

- Number of Parameters: Approximately 568 million.
- Layers: 16 Transformer layers in both the encoder and decoder.
- Hidden Size: 1024 hidden units.
- Attention Heads: 16 attention heads.

## Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/Fine_Tuning_Pegasus.git
cd Fine_Tuning_Pegasus
Install the required dependencies:
sh
Copy code
pip install -r requirements.txt

#To load the model in GPU

device = "cuda" if torch.cuda.is_available() else "cpu"


Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
```

## Test Case
- Dialogues
![Screenshot 2024-08-09 152951](https://github.com/user-attachments/assets/7e4fdda5-16de-43e1-8078-96a0ef3db553)

- Summaries
![image](https://github.com/user-attachments/assets/c2eb6512-ae08-4072-9336-15007ae6a710)
