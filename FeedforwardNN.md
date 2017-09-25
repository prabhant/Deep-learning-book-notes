# Notes

* Composition of linear finction is not very helpful as it will generate another input in the end so we can do the same work with few weights in the begining 
* Depth of the neural networks helps with the non linear functions mailnly 
* the model of the neural network describes some conditional probablility
* NN is just a concatonation of layes 

### Output units
* sigmoid function can be used in binary classification as it taked n number of input values and convert them in the form of values between 0-1
* sigmoid is coupled with the log function(cost function)
* sigmoid goes very well with maximum liklihood
* log can help with the saturation in the case of sigmoid(more in backprop)
* Softmax(multinoulli): generalize whhen we have morethan two classes
* softmax can be numerically unstable 
* softmax(z)=softmax(z=maxzi) : this one is more numerically stable
* softmax layer amplifies/maximizes the distance between the outputs a lot

### Hidden units
* ReLU : more numerically stable, better condition for gradient, sparse activation, mostly used, 
* sigmoids are usually used for RNNs, saturation for large Z, more difficult for train
* other units: cos, 

### Universal approximation theorem
* states that we can represent any function with number of layers
* not very helpful during ht epractical representation of NN
* usually overfits the data

**Advantages of having more than 1 hidden layers**
* You have more parameters to tweak with in the layes
* but just more parameters wont help
