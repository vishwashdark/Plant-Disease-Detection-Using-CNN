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

![image](https://github.com/vishwashdark/Plant-Disease-Detection-Using-CNN/assets/92641662/b35f9642-1357-4f1a-86fb-84eee89a55f4)


The accuracy and loss graph for the cotton model is a way
more uniform than the apple model, the value of accuracy
reaches 1 at 10 epochs which shows the model starts overfitting
after 10 epochs.
2) Testing the Model with Validation dataset: We will be
using the validation dataset to load all images into the model
to know the real time accuracy of the model.


![image](https://github.com/vishwashdark/Plant-Disease-Detection-Using-CNN/assets/92641662/5bdea1fb-5cf6-401d-9cd8-e72ecac7900a)

With the validation data-set our model has a very good
accuracy.This shows that the model can be used in real time
scenario with some modifications. Overall the model has
achived the average accuracy of 95.76These results indicate
that the model is performing well in distinguishing between
the Diseased leaves and the Healthy leaves which is essential
for your Plant disease Modification Model.
Table 7

![image](https://github.com/vishwashdark/Plant-Disease-Detection-Using-CNN/assets/92641662/002591d5-84f5-44b4-b51f-2fc3f500ce1d)


With the validation data set our model has a little less
accuracy than our Cotton model but it still has a good
average accuracy of 85%. This indicates that the model will
predict the correct results most of the time.There can be
some limitations at extreme cases which can be fixed by fine
tuning the model further.


3) Tkinter: We further went ahead and made a GUI which
could help us in making the model More user friendly so that
anybody can learn to use it.

Figure :Tkinter UI
![image](https://github.com/vishwashdark/Plant-Disease-Detection-Using-CNN/assets/92641662/428b3b01-7981-4be6-a09a-901cf8aaad3d)

In this UI there are 2 things which we can do either check
apple disease or cotton disease leaf.


Figure: Tkinter UI uploading Image
![image](https://github.com/vishwashdark/Plant-Disease-Detection-Using-CNN/assets/92641662/1319a35b-80cc-4121-9752-62af1f84ccc2)


In this UI page we can upload our the image of the Diseased
leaf to know the output.


In addition to these technologies, the integration of Chat
GPT has further enhanced the system’s capabilities. With the
Chatbot GPT integration, users can interact with the system
in a conversational manner, gaining insights into various plant
diseases, their symptoms, and recommended treatments. The
Chatbot serves as a knowledgeable virtual assistant, helping
users to understand the impact of the disease on the plants, and
make informed decisions about disease management strategies.
Overall with the Addition of the GUI, our project can do
various tasks all the way from having a better infrastructure
from sharing and storing images to sharing and storing the
trained models. Having a good and simple GUI so that
everyone can use them easily and with the power of ChatGPT
it can be used to take better and faster decisions to help the
farmers in treating the plants.
