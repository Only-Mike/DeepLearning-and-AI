# Bot for asnwering questions about ADHD <br>
<br>
*** This assingment is created by Lina, Snorre and Mike *** 
<br>
For this assingment we have created a simple question answering bot using the "distilbert-base-uncased" model from Huggingface 
<br>
The model is then trained on a ADHD dataset created by ChatGPT with the prompt: 
<br>
<br>
Can you create a dataset for a question answer model? <br>The dataset is being used for a proof of concept chatbot in which people can ask question about ADHD <br>
The data has to be in following columns in this order: 
<br>
id 
<br>
title (This has to be ADHD or related to ADHD) 
<br>
context 
<br>
question (has to be questions about ADHD) 
<br>
answers 
<br>
<br>
The dataset is comprimised of 38 rows which each of the questions, answers and context.
<br>
<br>

## Training 
The distilbert-base-uncased is after some testing, then trained on the dataset with these parameters
<br>
learning_rate=2e-5, <br>
per_device_train_batch_size=16, <br>
per_device_eval_batch_size=16, <br>
num_train_epochs=40, <br>
weight_decay=0.01, <br>
<br>
After the training and testing the model it was pushed to HuggingFace as a model.

## Gradio on Huggingface
For showcase, our model is then deplyed on HuggingFace using Gradio for people to test out <br>
Link to HF --> https://huggingface.co/spaces/Only-Mike/ADHD_QA_Bot

## Conclusion to QA bot <br>
Our QA model is working, but gives short answers without giving additional information to the one using the model. <br>
<br>

