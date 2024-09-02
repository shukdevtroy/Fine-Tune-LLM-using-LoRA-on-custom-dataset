# This is a custom dataset fine tune llm model using LoRA

### Run the code in Google Colab ---> Change Runtime to "T4 GPU" for faster training 

# DistilBERT-base-uncased LoRA Text Classification Model

## Model Description
This model is a fine-tuned version of `distilbert-base-uncased` on an unspecified dataset. It achieves the following results on the evaluation set:

- **Loss:** 0.4649
- **Accuracy:** 84.16%

## Intended Uses & Limitations
More information needed.

## Training and Evaluation Data
More information needed.

## Training Procedure

### Training Hyperparameters
The following hyperparameters were used during training:

- **Learning Rate:** 0.001
- **Train Batch Size:** 4
- **Eval Batch Size:** 4
- **Seed:** 42
- **Optimizer:** Adam with betas=(0.9,0.999) and epsilon=1e-08
- **LR Scheduler Type:** Linear
- **Number of Epochs:** 10

### Training Results
| Epoch | Training Loss | Validation Loss | Validation Accuracy |
|-------|---------------|-----------------|---------------------|
| 1.0   | 0.5924        | 0.5523          | 78.45%              |
| 2.0   | 0.5983        | 0.5236          | 80.29%              |
| 3.0   | 0.5703        | 0.4498          | 79.56%              |
| 4.0   | 0.5526        | 0.4976          | 80.66%              |
| 5.0   | 0.5326        | 0.4317          | 80.85%              |
| 6.0   | 0.5851        | 0.4562          | 82.87%              |
| 7.0   | 0.5466        | 0.4713          | 81.95%              |
| 8.0   | 0.5494        | 0.5072          | 82.50%              |
| 9.0   | 0.5748        | 0.4802          | 82.87%              |
| 10.0  | 0.5001        | 0.4649          | 84.16%              |

## Framework Versions
- **PEFT:** 0.12.0
- **Transformers:** 4.42.4
- **PyTorch:** 2.4.0+cu121
- **Datasets:** 2.21.0
- **Tokenizers:** 0.19.1

# Dataset Viewer

You can view the dataset using the following link:

[View Twitter Sentiment Preprocessed Dataset](https://huggingface.co/datasets/shukdevdatta123/twitter_sentiment_preprocessed/)

Simply click the link to open the dataset viewer in your browser.

# Model Viewer

You can view the model using the following link:

[View Model in HuggingFace](https://huggingface.co/shukdevdatta123/distilbert-base-uncased-lora-text-classification/)

Simply click the link to open the model file in your browser.


