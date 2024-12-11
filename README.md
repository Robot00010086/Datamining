# Datamining
datamining group project

SA_model_finetune.ipynb    finetune pre-trained Llama2-7b model for Sentimental Analysis
create_dataset.ipynb       translate int English with pre-trained MBart50 
filter_dataset.ipynb         drop bad records using Sentimental Analysis and NA checker,create the final dataset
model_predict.ipynb(implementing)     predict score using other features of each record
all-data.csv                    original dataset

trained_weights/*        finetuned Llama2-7b Lora parameters and tokenizer
output/*                  intermediate datasets (csv files）
merged_model/*            finetuned Llama2-7b parameters(merged lora parameters and original parameters)
input/*                    pretrained MBart50 parameters and LLama2-7b parameters
filtered_dataset/*        final dataset