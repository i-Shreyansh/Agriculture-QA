# Agriculture-QA

This repository contains the code and resources for the **Agriculture-QA** project, which fine-tunes the **LLaMA-3-2-3B** model using the **Unsloth adapter** with **LoRA** for the task of question answering in agriculture.

## Project Overview

The model is trained on a custom dataset for answering agriculture-related questions. The fine-tuned model, **fine-tuned-llama-3-2-3b-instruct**, is saved on Hugging Face under the repository `ShuklaShreyansh/Agro-QA`, which is currently public.

### Model

- **Fine-tuning method**: Used **Unsloth adapter** with **LoRA** to fine-tune the LLaMA-3-2-3B model.
- **Saved Model**: [ShuklaShreyansh/Agro-QA](https://huggingface.co/ShuklaShreyansh/Agro-QA) (Public).
- A new model version **ShuklaShreyansh/Agriculture_QA** will be released soon and will run on a Hugging Face Space.

## Files & Resources

1. **Kaggle Notebook**: A notebook for fine-tuning the model can be found [here](https://www.kaggle.com/code/shreyanshmanavshukla/agriculture-qa-fine-tuned-llama-3-2-3b-instruct).
2. **Dataset**: The dataset used for training and testing can be accessed [here](https://www.kaggle.com/datasets/shreyanshmanavshukla/agriculture-qa). The dataset is modified for question answering purposes.
3. **Requirements**: All the necessary dependencies are listed in the `requirements.txt` file.
4. **Dataset Folder**: The folder containing the dataset has been uploaded here.

## Setup

1. Clone the repository to your local machine.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
