Detecting Plant Diseases at Scale: A Distributed
CNN Approach with PySpark and Hadoop


This project aims to assist farmers in detecting plant
diseases by capturing pictures of leaves and analyzing them
using advanced technologies. The approach utilizes Convolutional
Neural Networks (CNN) to train a model on the collected
leaf images. To efficiently handle large-scale data, Pyspark, a
Python library for distributed data processing, is employed. It
leverages the capabilities of the Hadoop environment to gather
and process the necessary data, ensuring access to the right
people for analysis. Additionally, the project incorporates Tkinter,
a graphical user interface (GUI) framework, to present the output
in an organized and user-friendly manner. The combined use of
CNN, Pyspark, and Tkinter enables accurate disease detection
and aids in providing timely solutions to help farmers effectively
manage plant health.



Results 

1) Accuracy and Loss during Epoch: The performance
of the model throughout training iterations (or ”epochs”) is
referred to as accuracy over epochs. One frequent evaluation
parameter for evaluating the effectiveness of a classification
model is accuracy. It displays the proportion of examples that
were correctly classified out of all the instances in the model.
The Accuracy over Epoch graph shows how the model’s
accuracy varies throughout each training epoch. It enables us
to track the model’s development as it learns over time. We
can identify instances of overfitting, over-specialization to
the training data, and poor performance on unobserved
data using these graphs.
When referring to the loss function calculated at each
training iteration or epoch during the training of the model,
we use the term ”loss over epoch.” The objective of model
training is to reduce the loss function, which measures how
well the model fits the training set of data. Nevertheless, there
is always a potential that the prediction will be off in other
scenarios and for unforeseen circumstances.


![image](https://github.com/vishwashdark/Plant-Disease-Detection-Using-CNN/assets/92641662/c70450f1-0ca7-4a82-9646-1ddcf649ef06)


Let us take a deeper look into the Accuracy and loss graph
in the Apple Model. So it basically shows us how the Accuracy
of the model is increasing with each iteration or Epoch and
the loss function is decresing over-time which is a good thing,
this shows that the model is perfoming well while training.
It shows that after 15 epochs the model has reached a perfect
accuracy of 1. This shows that the model is a little overfitting.

