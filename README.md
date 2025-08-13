# poetic-style-transfer-llm-training
This project explores poetic style transfer, an NLP task where a language model is fine-tuned to rewrite modern poems by Robert Frost in the tone, structure, and voice of a Shakespearean sonnet.

# How to run this code
1. Copy the content of poem_transformations_project.ipynb to your clipboard 

2. Open [Google Colab](https://colab.research.google.com )

3. Paste the contents of the clipboard in a file and click the 'Run all' button at the top of the file

4. You will need a wandb key in order to train. You can find one here: [wandb key](https://wandb.ai/authorize?ref=models)

# Dependencies and setup steps
Once you have completed the steps above, it will install all dependecies required to run the code, including: 
1. transformers
2. datasets
3. accelerate
4. rouge-score
5. nltk
6. evaluate

# Files, Folders, Outcome
This project was done in a single file, as the dataset was manually entered and not imported from an external source. You should have access to the .ipynb file, which contains the code to run in Google Colab, as well as this current markdown file

Once the code is pasted into Google Colab and the user clicks 'run all', you should see the outcomes of the training, evaluation, and the final output after training. You are able to play around with it and add more data, use a different poem or lines for test_data, etc.
