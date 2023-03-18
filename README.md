### Fashion-Items-Image-Classification-With-One-Hidden-Layer-Using-Parallel-API
'''
Build feedforward neural network with 3 layer: input layer, one hidden layer và output layer
Dataset: Fashion-MNIST https://www.kaggle.com/datasets/zalando-research/fashionmnist 
Activation function: logistic       
Loss function: MSE 
Learning rate: 0.05 
Parallel API: OpenMP 
Programming language: C 
'''

Run program with 100 epochs <br />
Program executes in 4 threads: <br />
      Time: 2962,47s <br />
      <br />
Confustion matrix for training dataset: <br />
<br />
5563.00 21.00    76.00	 115.00	 24.00	 0.00	   542.00	 1.00	   35.00	 2.00 <br />
6.00	  5830.00  6.00	   27.00	 8.00	   0.00	   13.00	 0.00	   7.00	   1.00 <br />
43.00	  9.00     5265.00 18.00	 289.00	 1.00	   289.00	 0.00	   38.00	 1.00 <br />
144.00  106.00   78.00	 5606.00 123.00	 2.00	   125.00	 1.00	   24.00	 0.00 <br />
27.00	  10.00    380.00	 156.00	 5377.00 1.00	   267.00	 0.00	   17.00	 0.00 <br />
3.00	  1.00	   6.00	   2.00	   0.00	   5856.00 3.00	   46.00   38.00	 27.00 <br />
177.00  17.00	   170.00	 58.00	 162.00	 0.00	   4721.00 2.00	   46.00	 0.00 <br />
1.00	  1.00	   2.00	   2.00	   0.00	   81.00	 1.00	   5798.00 22.00	 104.00 <br />
31.00	  5.00	   17.00	 14.00	 17.00	 17.00	 38.00	 12.00	 5765.00 3.00 <br />
5.00	  0.00	   0.00	   2.00	   0.00	   42.00	 1.00	   140.00	 8.00	   5862.00 <br />
<br />
Confusion matrix for testing dataset:<br />
<br />
836.00 7.00	  14.00	 39.00	3.00	  1.00	 181.00	0.00	  6.00	  1.00 <br />
0.00	 969.00	1.00	 10.00	0.00	  0.00	 5.00	  0.00	  0.00	  0.00<br />
12.00	 3.00	  783.00 11.00	75.00	  1.00	 87.00	0.00	  10.00	  0.00<br />
34.00	 14.00	21.00	 888.00	25.00	  1.00	 35.00	0.00	  7.00	  1.00<br />
2.00	 3.00	  99.00	 34.00	818.00	0.00	 78.00	0.00	  3.00	  0.00<br />
1.00	 1.00	  1.00	 2.00	  1.00	  924.00 1.00	  26.00	  13.00	  16.00<br />
103.00 3.00	  76.00	 14.00	73.00	  1.00	 593.00	0.00	  17.00	  0.00<br />
1.00	 0.00	  0.00	 0.00	  1.00	  40.00	 0.00	  910.00	3.00	  37.00<br />
10.00	 0.00	  5.00	 2.00	  4.00	  6.00	 20.00	0.00	  938.00	0.00<br />
1.00	 0.00	  0.00	 0.00	  0.00	  26.00	 0.00	  64.00	  3.00	  945.00<br />
<br />
Accuracy score on training dataset: 92.7%<br />
Accuracy score on testing dataset: 86%<br />
Overall accuracy score: 91.8%<br />
<br />
I program in C language because normally C is faster more than 10 times than Python<br />
<br />
For more detail about dataset and algorithm read file report.pdf<br />
