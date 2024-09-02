# This is a custom dataset fine tune llm model using LoRA

### Run the code in Google Colab ---> Change Runtime to "T4 GPU" for faster training 

distilbert-base-uncased-lora-text-classification
This model is a fine-tuned version of distilbert-base-uncased on an unknown dataset. It achieves the following results on the evaluation set:

Loss: 0.4649
Accuracy: {'accuracy': 0.8416206261510129}
Model description
More information needed

Intended uses & limitations
More information needed

Training and evaluation data
More information needed

Training procedure
Training hyperparameters
The following hyperparameters were used during training:

learning_rate: 0.001
train_batch_size: 4
eval_batch_size: 4
seed: 42
optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
lr_scheduler_type: linear
num_epochs: 10
Training results
Training Loss	Epoch	Step	Validation Loss	Accuracy
0.5924	1.0	10744	0.5523	{'accuracy': 0.7845303867403315}
0.5983	2.0	21488	0.5236	{'accuracy': 0.8029465930018416}
0.5703	3.0	32232	0.4498	{'accuracy': 0.7955801104972375}
0.5526	4.0	42976	0.4976	{'accuracy': 0.8066298342541437}
0.5326	5.0	53720	0.4317	{'accuracy': 0.8084714548802947}
0.5851	6.0	64464	0.4562	{'accuracy': 0.8287292817679558}
0.5466	7.0	75208	0.4713	{'accuracy': 0.8195211786372008}
0.5494	8.0	85952	0.5072	{'accuracy': 0.8250460405156538}
0.5748	9.0	96696	0.4802	{'accuracy': 0.8287292817679558}
0.5001	10.0	107440	0.4649	{'accuracy': 0.8416206261510129}
Framework versions
PEFT 0.12.0
Transformers 4.42.4
Pytorch 2.4.0+cu121
Datasets 2.21.0
Tokenizers 0.19.1
