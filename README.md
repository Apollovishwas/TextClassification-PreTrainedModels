# TextClassification-PreTrainedModels

Bert Based Models:

All bert based models 12 Layers and 110M parameters with 768 Hidden and equal embedding layers. Since, BERT base consists of 110 million parameters which makes it computationally intensive and therefore a light version was required with reduced parameters, which is Alberta.  RoBERTa stands for “Robustly Optimized BERT pre-training Approach”. In many ways this is a better version of the BERT model. The key points of difference are  Dynamic Masking, Large Batch size, More data Points. Unlike the other variants which tweaked some aspects of the BERT model to create a new version, DistilBERT works in a different manner.This variant do not tweak the model but try to reduce the size of the model by creating a smaller model which somehow replicates the output of the bigger model.The process is called knowledge distillation. Hence the name. 



Text Classification Accuracies:

Albert	77.45%
Roberta	95%
BART	~100%
DistillBert Base Cased	91%
BERT Base Cased	51%
