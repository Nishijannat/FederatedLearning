# FederatedLearning

**Federated Learning Algorithm on Image Data**

_The need for user data training is significant in technology development, necessitating the use of machine 
learning approaches. Conventional learning methods collect data from individual devices and send to a 
common server, which can harm data and slow. Federated Learning, a machine learning method, can help 
train data without sharing it with any common server, rather it uses local data to train a common model on 
their own platform or device. After training, corrected weights or model updates are sent to a central server for 
further development. This approach saves bandwidth and makes the process faster.
Before training globally in the central server, it assigns a model to locally to each device, which then trains 
the model using its own data with Stochastic Gradient Descent (SGD) algorithm. After this Each device sends 
back only the updates as weights, to the central server. The collected weights are averaged which helps to 
improve the model for training repeatedly until fully trained. In the paper datasets form MNIST, CIFER are 
used for learning even with non-independent and identically distributed data. It has been proved that, 
Federated Averaging works well even Non-IID and Unbalanced Data which are not evenly distributed or not 
from same probability distribution_**
**
Output:****
In conclusion, the whole algorithm can be divided into two parts- improving locally training model on 
batches of data with this happening on the respective devices of the users and sending locally run output –
weights and losses to the global model and as now the server knows where to improve train a percentage of all 
clients data centrally. That again sends the updates to the first part of this algorithm for local model to 
improve more and send update again to the global model until the whole training is complete for all the data.
