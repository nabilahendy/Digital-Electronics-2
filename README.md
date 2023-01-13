# Digital-Electronics-2
# Coursera machine learning

This course wantds to show how Machine Learning can be used to solve problems and its limitation. We are going also going to learn about how embedded systems,
such as single board computers and microcontrollers can be effectively used to solve problems and créate new types of computer interfaces. 

### WEEK 1

When we think of machine learning, we usually think of powerful servers crunching tons of data in order to do things like filter out spam emails, recommend movies for us to watch and predict traffic patterns during our commute.

The prerequisites that we should be fmiliar with are the algebra and Arduino. To complete the course, we will need a modern smartphone with a browser and optionlly, the Arduino Nano 33 BLE Sense board. 
An Embeded system is any computer system that is contained or embedded inside of another larger mechanical or electrical system. 
In the next picture, it shows the calification of a Little test of five questions: the first one, talks about how the AI is only concerned with the designing and building of intelligent agents that receive precepts from the environment and discover patterns in that environment, wich is false,  for something to be considered AI, it must take action that affect that environment. The second question was aboutclassification being a supervised learning for Machine Learning. The third one was about how the training pase is where the model’s parameters get updated. About the fourth question its about how the mchine learning models are prone to biases in the data. The last question, and the most interesting one in my opinión, was about how on an AI system it important to build a societal trust with ethical, in order to maintain a leve lof fairness. 

![image](https://user-images.githubusercontent.com/115028247/211308644-4c87fe94-6a05-46d6-a4e5-e313b5d27f34.png)

The first part of this point, shows us the importance of single board computers. 
So that, they have more powerful microprocessor with separate memory. 
This characteristic can make them capable of running a full operating system like Linux,
and also provide a full user interface. Unlike microcontrollers, 
these are much cheaper but les powerful.  

In the next picture, we can se the differences between single board computer and microcontrollers:

![image](https://user-images.githubusercontent.com/115028247/211308771-f47cedc2-67a0-4f94-bd1e-17fb21f585de.png)

Moving to another subject, we also learned about tinyML, wich responds to Tiny Machine Learning. It can be defined as a Dynamic field os computer science that has permeated nearly every digital thing that we interact with. It can be social media, our cell pones, our cars… 
Machine learning itself can be a technology that utilizes algorithms called “neural networks” to teach a computer to recognize patterns. As we can see in the next picture:

![image](https://user-images.githubusercontent.com/115028247/211308810-0eaa36ad-0c6a-48c3-960f-39c763dfe0ae.png)

With this course, we learned that tinyML can be classified inte three domains: vibration, voice and visión. Vibration includes control and localization, voice include systems with microphones and visión includes system recognizing. Al lof these three domains or 3D’s have different workload performance requirments and demand scalable solutions.
As in all the points of this course, at the end of these, we have a small questionnaire about the information we saw. In the next picture, there is the mark obtained:

![image](https://user-images.githubusercontent.com/115028247/211308850-bc0cd336-b29c-470e-9304-6b66323b499f.png)

In this point, we learn about how Machines can learn to recognize gestures like left to right, up and down and moving in circles a device. We see an example of a data recollecting with a mobile phone, connecting this one to smarphone.edgeimpulse.com. They show us how to start sampling the information of the moves that we do with the phone, repeating this process until they 200 seconds of data. Once they have the data for left to right, up and down and circles moves, we can see how it creates a model that can recognize all these different motions. 
In the next picture, we can see how the training set works:

![image](https://user-images.githubusercontent.com/115028247/211356569-96fb841a-8182-4db3-9b25-7f1390c5c331.png)

Moving to the extraction data, we have to know that this is one of the most important things that we can do with machine learning. The point is about figuring out how to extract data and send it to our model for training and interference. 
Its interesting to know the definition they give to the “Feature”, and this is explained like  an individual measurable property of a phenomen being observed. We will use this features and associated labels to train the device or model. 

### REVIEW
In the review, we make a little test of 10 questions about everything that we saw in the other points above:

![image](https://user-images.githubusercontent.com/115028247/211356969-214d3fa2-cdef-4b7a-806e-df6c8e5b52e6.png)



### WEEK 2

As we can see in the next picture, the resulto of a clculation, that we are going to call “Output”, is the re-transmitted data whose signal strength is adjusted by neuronal weights:

![image](https://user-images.githubusercontent.com/115028247/212354309-0ba04ca7-0321-4a5d-958e-24cbe3fe6b73.png)

This artificial neural networks, are models with hidden layers. Every layer is densley connected with the previous and the next one. 
In the next picture, we are going to see one of the most interesting things, in my opinión, about neural networks, and it’s the comparation between an artificial network and a biological one:

![image](https://user-images.githubusercontent.com/115028247/212354367-517d274e-4bb8-48bb-a957-9e755121270c.png)

To build an artificial network, there is something called “Recipe” composed of the input, the comparation unit (a linear funciton and an activation fucntion) and the output. 

Fort he model training in network, there is some interesting concets that we should know about: one of them is the activation function, this one is requires so that the node does not act as a regression función. We will explain it better:
The next picture shows a neural network architecture, it is a simple three layer neural network. In the course, they explain use that each layer consists of a set of fully connected nodes. The first layer consists of 20 nodes and the input are stored as a 33 element array. Each element is copied to each node in the first layer, and each node then performs the clculations on the inputs, this means that there is a multiplication for each input, adding a constant (bias term) to finally summing them. The sum goes through a non-linear funciton to give each node its decisión making ability. Then, this output is copied to every node in the second layer. This process it is going to repeat all over again, but with different set of nodes.

![image](https://user-images.githubusercontent.com/115028247/212359818-93ed0d9b-2789-4cc9-9ba6-d80977e905df.png)

![image](https://user-images.githubusercontent.com/115028247/212359845-22a74576-48bd-481e-aa99-e934bf3ce173.png)

Reviewing the information above, a single node in a neural network start with the action of multiplying each input value by a weight, then sums the products of step 1, then adds a bias term to the sum computed in step 2 to finally aply an activation funciton to the sum from step 3 to produce a single value output.

Another interesting concept it is de “Back propagation”, this is a widely used algorithm for training feedforward artificial neural networks. This term, refers only to the algorithm for computing the gradient, and not how the gradient is used. 




### WEEK 3



### BIBLIOGRAPHY
- What Is TinyML? - Technical Articles (allaboutcircuits.com)
- https://blog.ovhcloud.com/what-does-training-neural-networks-mean/
- https://en.wikipedia.org/wiki/Backpropagation
