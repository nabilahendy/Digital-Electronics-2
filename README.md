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

We learned, that evaluating a model is one of the most important things, since it help us determine if the model that we are building, is capable of meet our needs. 
One of the most useful evaluation tools is the confusion matrix. Is a specifica table layout that allows visualization of the performance of an algorithm, normally a supervised learning. The confusion matrix tabulates al lof the correct and incorrect responses a model produces given a set of data. 
For example, we have a sample of 12 individuals, 8 of them are positive in covid and 4 of them are negative. Positive individuals belongs to class 1 and negativo individuals belongs to class 0. So now we have the next image: 
![image](https://user-images.githubusercontent.com/115028247/212484766-7741201c-8f98-453e-acc3-1b1d2578c11b.png)

We asume that we have a classifier that distinguishes between positive and negative individuals, so we can take the 12 of them and run them through the classifier. This one will make 9 accurate prediction. But the interesting thing it is that the classifier predicts 2 individuals that are fake negative (1 and 2) and one person with fake positive (9):

![image](https://user-images.githubusercontent.com/115028247/212484783-250ceaa5-3ba1-4ce9-9bb5-209a2b087583.png)

Comparing the actual classification with the predicted one, we can notice 4 different outcoums: 
1.	The actual classification is positive and so it is the predicted one (1,1)
2.	The actual classification is positive and the predicted one is negative (1,0)
3.	The actual classification is negative and so it is the predicted one (0,0)
4.	The actual classification is negative and the predicted one is positive (0,1)
Then, we can perform the comparison between actual and predicted classifications, adding information to the table: 

![image](https://user-images.githubusercontent.com/115028247/212484804-08b51184-b1a7-41f4-9106-acedd570f1fa.png)

(the green results are the correct one)
The template for any binary confusión matrix uses the four results discussed above along with the positive and negative classifications. Then the four outcomes can be formulated as a  2x2 confusion matrix:

![image](https://user-images.githubusercontent.com/115028247/212484812-4c527ac7-55c2-405e-8a5d-b3a17c284b08.png)

In this confusión matrix, 8 of the simples with positive in covid, we know that the system will judge that 2 were fake positive, and for the 4 samples with negative in covid, it will predict that 1 is fake negative. The correct predictions are located in the green highlighted, and the error with red. By summing up the 2 rows of the confusión matrix, one can also deduce the total number of positive and negative simples in the original dataset. So we will have P= TP + FN and N= FP + TN.

IT also would be nice to explain, what Anomaly detection is: we can define it as a process of identifying unexpected items or events in data sets, wich differ from the norm. Anomaly detection has two basic assumptions: anomalies are rare in data and their features differ from the normal instances significantly.



### WEEK 3-

We can define the classification of audio as a useful application of machine learning. The are lot’s of examples, but one of the most interesting  is  the home smart speaker. We can highlight the Amazon Echo internally a microcontroller, which after listening to the keyword Alexa,  starts to stream the audio to the servers where much more complicated machine  learning algorithm process the user request.

If we want to create a model that recognize our keywords, we have to generate some features: volume, position... Joseph Fourier in 1800's developed a technique wich is based on that any repeating signal can be represented by an infintite sum of sine and cosine waves at different frequencies. This is what nowadays we call Fourier Transform, wich allows us to break any signal into its frequency components. Every audio record consists of a series of equally spaced samples rather than a continous line, and this is why we need to use discrete Fourier Transform. 

Another important concept, it's Convolutional Neural Network, and this is a class of artificial neural network applied to analyze visual imagery. They are based on the shared-weight architecture of te convolution kernels or filters that slide along input features and provide translation-equivariant responses also known as feature maps. They are regularized versions of multilayer perceptons, wich means fully conected networks, that is, each neuron in one layer is connected to ll neurons in the next one. This convolution layers contain filters whose parameters are updated just like the parameters in regular neural network node. In another words, they are trainable using black propagation. 

![image](https://user-images.githubusercontent.com/115028247/212993260-2d5bdf11-a3ea-48ea-9533-71d9cea4d0da.png)

In the next point, we are going to put all this concepts and some more into practice.

### PROJECT: Sound Classification
The idea of this project is to create a speech recognition system. We will start with a simple, pre-made dataset, add our own trget sound, and build a classifier for those sounds. 
The required hardware for collecting data should have access to a recording device. Thats why we are going to use our own smartphone. As we do not have access to Arduino, we won't be using it. 
With Edge Impulse, we are going to start pre-mading the dataset. First of all, we upload the 480 voice archives: 

![image](https://user-images.githubusercontent.com/115028247/212745376-6d54cfc9-0536-4126-96b3-75bd4c92236f.png)

Once we have our data uploaded, we can see it in our Data acquisition:

![image](https://user-images.githubusercontent.com/115028247/212995852-af731a48-53c9-489f-a342-9e5ced9d0d00.png)


Moving to the Feature Extraction, we create an Audio (MFCC) and then a Neural Network (Keras) learning blocks:

![image](https://user-images.githubusercontent.com/115028247/212995824-c395276b-3e19-4532-8241-6f6bf3d552eb.png)

After this, we go to the MFCC page and we generate features. This will show us how our audio samples are convertted into spectrograms. As we can see in our result, our features are separated very well. This will make it more easier if we want to create an accurate model:  

![image](https://user-images.githubusercontent.com/115028247/212996157-b6137f18-7ca7-449f-8fad-4de39ecdc68c.png)

In the Classifier page, we start training tho see de Confusion Matrix (a concept that we talked about earlier) of the validation data. 
 
Finally, after all this steps, we should test the model and classify all of the test data to then try it with our smartphone and see if it can recognize the sound.



### CONCLUSION

With this course, we learned that Machine Learning it is a very broad subject, full of mathematical and engineering concepts that must be controlled perfectly, that also will be in a constant evolution, since we see new concepts and methods everyday. Wich means that we will never stop learning about it. 


### BIBLIOGRAPHY
- What Is TinyML? - Technical Articles (allaboutcircuits.com)
- https://blog.ovhcloud.com/what-does-training-neural-networks-mean/
- https://en.wikipedia.org/wiki/Backpropagation
- https://en.wikipedia.org/wiki/Confusion_matrix
- https://towardsdatascience.com/anomaly-detection-for-dummies-15f148e559c1
- https://en.wikipedia.org/wiki/Convolutional_neural_network
