Group 20: Hasan , Ahmed 

UI LLM- Conversational AI with LoRA

https://67ea5c508f06eb5bc0.gradio.live


# Task2


Model-centric approach :

In order to improve the performance we can fine tune different hyperparameters. For instance we fine tune the learning rate. When the learning rate is too high then it will not converge and the model will not reach the optimal solution. When the learning rate is too low, get stuck in a local minimum. Therefore making  a grid search to find the optimal learning will lead to better performance since it will not get stuck in local minimum.  

We can also use scheduled learning rates such as cyclic learning to improve the performance. 

Another step is to find the suitable weight decay. Weight decay is a regularization technique  that can be used to avoid overfitting. Therefore a grid search to find the optimal weight decay will lead to better performance since it reduces the complexity of the model.   



Data-centric approach :
Another dataset that be used it the LIMA : https://paperswithcode.com/dataset/lima
According to the article, the dataset helps the model generalize better and can do many diiferent tasks.
