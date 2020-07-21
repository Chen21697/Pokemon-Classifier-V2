# ML Logistic Regression Practice
This project is a practice based on professor Hung-Yi Lee's ML Lecture. Notice that it is a binary case, Class1 is Grass type and Class0 is Fire type.

I used six features (HP, Attack, Defense, Sp. Atk, Sp. Def, Speed) as the input, each feature has its own coefficient.

In the end of this project I use the same training and testing set on Sklearn's Logistic Regression model, comparing the coefficients and accuracy I got using my own code. Eventually, the result of the optimal coefficients is [0.015, -0.017, 0.011, -0.019, 0.010, -0.008] and the accuracy is 0.707, which are almost the same as using Sklearn's Logistic Regression model.


#### Professor Hung-Yi Lee's profile: http://speech.ee.ntu.edu.tw/~tlkagk/courses.html
#### Dataset: https://www.kaggle.com/abcsds/pokemon
