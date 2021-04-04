# Simple-Neural-Network
Train a simple neural network using non-linear least squares algorithms (Levenberg-Marquardt), and test them to approximate certain non-linear functions. 

## Simple Neural Network
A neural network is widely used parametric model to approximate non-linear functions. These networks are parameterized by a set of weights. Neural networks are often referred to as “universal approximators", which means that they can approximate a large class of non-linear functions by suitably tuning the weights. Here I programmed a simple neural network to approximate different types of non-linear functions using “non-linear" least squares algorithms learned in lectures.   
A neural network is a model of the form  
![image](https://user-images.githubusercontent.com/44150278/101875651-f29e7880-3bc5-11eb-9d22-d16d2e55df59.png)  
![image](https://user-images.githubusercontent.com/44150278/101875594-d7336d80-3bc5-11eb-9b62-5a7dba15bd93.png)

I used sigmoid as our psi function.   

The non-linear function to approximate is  
![image](https://user-images.githubusercontent.com/44150278/101875817-44df9980-3bc6-11eb-9a84-f2b6a969a799.png) <\ br>
and
![image](https://user-images.githubusercontent.com/44150278/101875887-63459500-3bc6-11eb-99f0-4023b86c3df4.png)

## Training
I used Levenberg-Marquardt algorithm to determine the weighhts for approximating different non-linear functions.   
  
![image](https://user-images.githubusercontent.com/44150278/101876160-ef57bc80-3bc6-11eb-8d8a-e25bc3577610.png)  
  
The loss function is defined as  
![image](https://user-images.githubusercontent.com/44150278/101876305-2c23b380-3bc7-11eb-9d0c-a071355bc28e.png)  
where _r_ is simply the difference between our prediction _fw_, and the ground-truth values _y_.
