# TextGenerator

The Text Generator is a recursive neural network that is made in Python with TensorFlow and keras, which are machine learning libraries. The output is actually still quite incoherent because the training data I chose James Joyce's Ulysses, so it reads like a strange text even with minimal loss.

For this project I used Google Collaboratory, it is similar to Jupyter Notebooks and also has different runtime methods which are great for AI and ML development since one of those methods has a GPU accelerator. So it is reccommended to run this in the same developer environment I used, Google Collaboratory, which is free and a fantastic all around resource.

The epochs or cycles of learning iterations is currently set to 50 in the source code, feel free to change it and see how the number of epochs can affect the learning capabilities of our RNN. Make sure to use the GPU feature in Google Collab!! Even with GPU acceleration enabled it takes 25 minutes. Eventually you reach a plateau unless you add on more data, so decrease in loss becomes minimal after a certain point.

Soon I will have this easily implemented on my personal website where a user can just input a string of text and receive the output of gibberish.

This is a rather simple implementation of neural networks, and although complex for regular standards of programs there are even deeper and more complex neural networks for a multitude of layers to obscure and weigh the data. This is where technology is headed so it is important to gain a coherent comprehension of this impressive functionality, especially when libraries like TensorFlow, keras, PyTorch, etc, make it so "easy" to use with their documentation and resources.

There are different types of neural networks, the one utilized in this is a recursive neural network, which has what is called LSTM or Long Short Term Memory allowing it to piece together text and create a prediction on what letter, word, and character comes next. It has a checkpoint based system and you can actually recall a certain iteration of its learning process and see how it evolved. 


Note: The code should work out of the box, so if it doesn't make sure to run each cell accordingly or just use Run All.
