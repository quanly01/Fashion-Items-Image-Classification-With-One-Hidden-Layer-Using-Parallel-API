### Fashion-Items-Image-Classification-With-One-Hidden-Layer-Using-Parallel-API
```
Build feedforward neural network with 3 layer: input layer, one hidden layer và output layer
Dataset: Fashion-MNIST https://www.kaggle.com/datasets/zalando-research/fashionmnist 
Activation function: logistic       
Loss function: MSE 
Learning rate: 0.05 
Parallel API: OpenMP 
Programming language: C 
```

```
Run program with 100 epochs 
Program executes in 4 threads: 
      Time: 2962,47s 
```

```
Confustion matrix for training dataset: 
 ```

|||||||||||
|------	|------	|------	|------	|------	|------	|------	|------	|------	|------	|
| 5563	| 21   	| 76   	| 115   	| 24   	| 0    	| 542  	| 1    	| 35   	| 2    	|
| 6    	| 5830 	| 6    	| 27   	| 8   	| 0    	| 13    	| 0    	| 7    	| 1    	|
| 43   	| 9   	| 5265 	| 18    	| 289   	| 1    	| 289   	| 0    	| 38   	| 1    	|
| 144   	| 106  	| 78  	| 5606 	| 123   	| 2    	| 125   	| 1    	| 24   	| 0    	|
| 27   	| 10    	| 380  	| 156   	| 5377 	| 1    	| 267  	| 0    	| 17   	| 0    	|
| 3    	| 1    	| 6    	| 2   	| 0    	| 5856 	| 3    	| 46   	| 38    	| 27   	|
| 177   	| 17    	| 170   	| 58   	| 162   	| 0    	| 4721 	| 2    	| 46   	| 0    	|
| 1    	| 1    	| 2   	| 2    	| 0    	| 81   	| 1    	| 5798 	| 22   	| 104   	|
| 31   	| 5    	| 17   	| 14    	| 17   	| 17    	| 38   	| 12   	| 5765 	| 3    	|
| 5   	| 0    	| 0    	| 2    	| 0    	| 42    	| 1    	| 140   	| 8    	| 5862 	|



```
Confusion matrix for testing dataset:
```

|||||||||||
|------	|------	|------	|------	|------	|------	|------	|------	|------	|------	|
| 836	      | 7   	| 14   	| 39  	| 3   	| 1    	| 181  	| 0    	| 6   	| 1    	|
| 0    	| 969 	| 1    	| 10  	| 0  	      | 0    	| 5   	| 0    	| 0  	      | 0   	|
| 12 	      | 3  	      | 784       | 11  	| 75   	| 1    	| 87   	| 0    	| 10   	| 0    	|
| 34   	| 14  	| 21  	| 888 	| 25   	| 1    	| 35   	| 0    	| 7   	| 1    	|
| 2   	| 3    	| 99  	| 34   	| 818 	| 0    	| 78  	| 0    	| 3   	| 0    	|
| 1    	| 1    	| 1    	| 2   	| 1    	| 924 	| 1    	| 26   	| 13    	| 16   	|
| 103   	| 3    	| 76   	| 14   	| 73   	| 1    	| 593 	| 0    	| 17   	| 0    	|
| 1    	| 0    	| 0   	| 0   	| 1    	| 40   	| 0    	| 910 	| 3   	| 37   	|
| 10   	| 0    	| 5   	| 2    	| 4   	| 6    	| 20   	| 0   	| 938 	| 0    	|
| 1   	| 0    	| 0    	| 0    	| 0    	| 26    	| 0   	| 64   	| 3    	| 945 	|

```
Accuracy score on training dataset: 92.7%
Accuracy score on testing dataset: 86%
Overall accuracy score: 91.8%
```

```
I program in C language because normally C is faster more than 10 times than Python

For more detail about dataset and algorithm read file report.pdf
```
