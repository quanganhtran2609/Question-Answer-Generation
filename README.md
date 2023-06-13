# Question-Answer-Generation

This project focuses on fine-tuning the mT5 (Multilingual T5) transformer model to generate Vietnamese question-answer pairs from an input paragraph, by using Python and Pytorch Lightning. The mT5 model is a state-of-the-art pre-trained language model developed by Google Research that supports multilingual text generation tasks.

**Features**
- Question-Answer Generation: The fine-tuned mT5 model takes an input paragraph in Vietnamese and generates high-quality question-answer pairs.
- Transformer-based Architecture: The project utilizes the powerful mT5 transformer model, which has shown excellent performance in natural language processing tasks.
- Customizability: The code allows for fine-tuning the mT5 model on different datasets, enabling adaptation to specific domains or use cases.
- Evaluation Metrics: The generated question-answer pairs are evaluated using ROUGE, BERTScore, and human evaluation to assess their quality and effectiveness.
- Preprocessing and Postprocessing: The project includes utilities for preprocessing the input paragraph and postprocessing the generated question-answer pairs to ensure accurate and readable outputs.

**Requirements**
bert_score          0.3.12
google              NA
numpy               1.22.4
pandas              1.5.3
pytorch_lightning   2.0.1
rouge               1.0.1
session_info        1.0.0
sklearn             1.2.2
torch               2.0.1+cu118
tqdm                4.65.0
transformers        4.27.4
