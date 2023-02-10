# CNN and LSTM <br>
<br>
*** This assingment is created by Lina, Snorre and Mike ***
<br>
For this assignment we have created a LSTM model and a CNN model <br>
The LSTM model is trained on weather data collected each month from 2000 to 2019. <br>
The dataset is downloaded from kaggle. <br>

## LSTM 1 <br>
input_size = 3 <br>
hidden_size = 16 <br>
output_size = 1 <br>
num_epochs = 10 <br>

## LSTM 2 <br>
input_size = 3 <br>
hidden_size = 16 <br>
output_size = 1 <br>
num_epochs = 100 <br>

## Conclusion to LSTM <br>
If looking at the two LSTM networks it clearly shows the LSTM network with 100 epochs is the more accurate one <br>
<br>
<br>
<br>

## CNN 1 <br>
num_epochs = 3 <br>
batch_size = 10 <br>
lr = 0.01 <br>
Also the stepsize in training is set to 1000 <br>

## CNN2 <br>
num_epochs = 100 <br>
batch_size = 10 <br>
lr = 0.01 <br>
Also the stepsize in training is set to 2000 <br>

## Conclusion to CNN <br>
CNN 1 was by far the most accurate one. <br>
The effiency is influenced by the number of epochs. <br>
To make the training process faster we increased the stepsize, which seemed to have little to no impact on the accuraccy. <br>