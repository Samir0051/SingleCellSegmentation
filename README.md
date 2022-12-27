# SingleCellSegmentation
Created By: Samir Sanchez Tejada, Sofia Garcia, Karolina Majewska 

Used a U-Net model to train a neural network (that is constructed using a training loop) that is then tested against a testing set sample.
In addition the optimizer function uses the ADAM algorithm and the loss function uses binary-cross entropy. 50 epochs were trained in total 
and then the best performing epoch was utilized to represented as the best model. The accuracy of the model was then tested to be about 98.4%. 
An accuracy and confusion matrix were then created to analyze the performance of the model by showing the true-positives that the model detected,
and the true negatives that the model detected.
