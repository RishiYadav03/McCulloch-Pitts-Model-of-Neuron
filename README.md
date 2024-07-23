# McCulloch-Pitts-Model-of-Neuron
The McCulloch-Pitts neural model, which was the earliest ANN model, has only two types of inputs — Excitatory and Inhibitory. The excitatory inputs have weights of positive magnitude and the inhibitory weights have weights of negative magnitude. The inputs of the McCulloch-Pitts neuron could be either 0 or 1. It has a threshold function as an activation function. So, the output signal yout is 1 if the input ysum is greater than or equal to a given threshold value, else 0. The diagrammatic representation of the model is as follows:

![model1](https://github.com/user-attachments/assets/0368747e-c3c6-4fdb-a5fd-c9dba6d12e45)

Simple McCulloch-Pitts neurons can be used to design logical operations. For that purpose, the connection weights need to be correctly decided along with the threshold function (rather than the threshold value of the activation function). For better understanding purpose, let me consider an example:

John carries an umbrella if it is sunny or if it is raining. There are four given situations. I need to decide when John will carry the umbrella. The situations are as follows:

First scenario: It is not raining, nor it is sunny
Second scenario: It is not raining, but it is sunny
Third scenario: It is raining, and it is not sunny
Fourth scenario: It is raining as well as it is sunny
To analyse the situations using the McCulloch-Pitts neural model, I can consider the  input signals as follows:

X1: Is it raining?
X2 : Is it sunny?
So, the value of both scenarios can be either 0 or 1. We can use the value of both weights X1 and X2 as 1 and a threshold function as 1. So, the neural network model will look like:

![model2](https://github.com/user-attachments/assets/166b09cd-c0f1-401b-89c3-07bb1c21e6ec)

