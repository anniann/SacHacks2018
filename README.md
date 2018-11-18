# **SacHacks2018**
___
Web application platform for customer support and service chat communication. 
***
Using the *Cloud Natural Language API* from the Google Cloud Platform, messages received from a customer are analyzed and given a sentiment value between [-1,1] with 1 being positive, -1 being negative, and 0 being neutral. Using this information, different customer messages are prioritized by the severity of their sentiments. The customer service agent can then draft a reply to the highest priority customers first. Before being sent, this reply is analyzed and also given a sentiment value. If the sentiment value is less than the absolute value of the customer's message's sentiment then a warning is given and rephasing of the message is recommended to the customer service agent. The application also has **speech-to-text** functionality through the *Cloud Speech API* from the Google Cloud Platform, which can be utilized for vocal communication. 
***
The intent of this platform is to foster positive customer support and service communication, increase customer retention rates through improved service, and gain insight into the sentiments behind communication.

#### -Annie Wong, Wyatt Walsh 


