# Automatic Code Flowchart Generation
Generate flowchart representations of Python code snippets 

# Dataset
We manually curated a dataset of 5000 Python code snippets collected from the CodeSearchNet corpus. 
- 3000 training code snippets and 1000 code snippets for testing and validation, respectively.
- Each set consists of a source folder with the Python code snippets and a target folder consisting of textual representations of these code snippets (flowchart DSL format).

# Model Architecture
Seq2Seq Architecture with GraphCodeBERT as the encoder and stacked transformer layers as the decoder.
- GCB_Translation.ipynb has the script to run the models
- The translation ability of the model is calculated using the BLEU score. Script in bleu.py.

