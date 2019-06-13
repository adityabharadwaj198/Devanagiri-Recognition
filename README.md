# Devanagiri-Recognition
Recognizing handwritten hindi alphabets using CNNs.

I trained a CNN on devanagiri dataset taken from the UCI ML repository. I used Keras for a higher level abstraction and Tensorflow as the framework.

The architecture is : input ==> convLayer ==> MaxPooling ==> convLayer ==> MaxPooling ==> FC ==> FC ==> softmax ==>result

Training accuracy = 98.59%

Testing accuracy = 98.15%
