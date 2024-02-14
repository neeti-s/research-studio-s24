# Title
**Interactive Machine Learning for Beginners**

## Abstract

Summarize your research project, including its objectives, methodology, and expected impact in 200-250 words.

This project aims at contributing to the principles of "Explainable AI", which emphasizes the importance of explainability and interpretability of machine learning models beyonds mere accuracy. In this project, I want to build an interactive demonstration of a well-known machine learning model (probably the neural network), which unveils its internal workings and allowing the viewers to modify the parameters. This facilitates artists in getting a better understanding of how everything works inside the "blackbox" and unlock their creative potential within their own ml5 projects. 

I will begin by dissecting the source code of the ml5.js neural network library, examining how it draws the data and the methods from the TensorFlow.js model, and exposing what's going on in the hidden layers. The ideal outcome will be a highly-interactive web project that intuitively shows the essense of neural network with interactive graphic elements.
Users can engage with the intermediate steps by modifying the parameters, watching animated process of certain functions, or accessing detailed data. 

I also want to make this web project easy to be embedded in webpages and easy to be replicated and further developed by an interested viewer.

Target audience: Artists and designers who want to understand and make use of machine learning in their works.


## Objectives

What are the objectives your project aims to achieve? Explain how these objectives contribute to the ml5.js project and/or the broader creative coding community.  

**Show the inner workings of the black box**
-  Instead of just generating the results of training, classification or regression, I want to answer the question: "What is exactly happening during the process?? How is the input data transformed in each layer and affects the output layer? How can the model achieve a better performance by iterating its training again and again? ..."   

**Be interactive**
- Users get highly engaged in the interactive process. They have the flexibility to modify the inputs, adjust the number of layers and nodes, experiment with the activation functions and so on. Through clicking on main processes of the training, they will see an animated illustration of how data is transformed in particular parts.

**Be replicable**
- Given that there are already many interactive visualizations of machine learning models (the most popular one is TensorFlow's neural network playground), I want to make my project more approachable for the beginners. By offering understandable explanations and accessible source code, the project aims to empower beginners to replicate and extend its functionalities. Users can leverage this project as a stepping stone in their journey from conceptual understanding to practical implementation of machine learning.


## References

Provide a list of existing literature, projects, or other work relevant to your project. Summarize key points and highlight gaps or opportunities your project seeks to address.

**Methodology** 
- [Explainable Artificial Intelligence (XAI): What we know and what is left to attain Trustworthy Artificial Intelligence](https://www.sciencedirect.com/science/article/pii/S1566253523001148) by Sajid Ali et.al  

**Technicals**
- [Transfer learning for image classification](https://medium.com/dataman-in-ai/transfer-learning-for-image-classification-1-all-start-here-8f88291b4d76) by Chris Kuo  

**Visualization**
- [Neural Network Playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.26008&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false) by TensorFlow
- [CNN Explainer](https://poloclub.github.io/cnn-explainer) by Jay Wang et.al
- [A visual introduction to machine learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) by R2D3


## Methodology

Detail the methods, techniques, or approaches you will use to achieve your project objectives. Include information on any tools and technologies you plan to use. Think about how your project engages with or contributes to the community. What kinds of user testing will you do?

1. Conduct user research to identify the interests and areas of confusion among potential users. It's important to have a 
2. Understand the logic of neural networks.
3. Get familiar with the ml5 neural network library methods, and their potential usage. If essential, bring new functions to draw data directly from TensorFlow?
4. Design interaction methods.
5. Implementation


## Challenges

What challenges do you anticipate encountering during your work? What kinds of support do you need to meet these challenges?

1. How possible is it to expose the intermediate layers by using the existing ml5 neural network methods?
- Yes, it's possible. Through ml5, we can get an object containing all the data of the imtermidate layer. However, it's still a challenge to extract the parts that make sense to the users.
2. There exists very similar projects. How can I produce some original outcomes?
- Firstly, the existings visualizations lack a context or background story of the data that is fed into the neural network, making them far away from real-world application. Therefore, I can pay attention to applying simple real world data as the source of visualization.
- Secondly, as one of the key objectives, I want to make my source code well-documented and easy-to-understand, so the viewers can replicate it and make further adjustments according to their need.
3. Tools or frameworks?

## Final Deliverable

Describe the form and content of your project for the final presentation. This could include software, documentation, a research paper.

## Timeline

Outline a plan, detailing what you aim to accomplish at each stage of your project. Include milestones, deliverables, and any deadlines. You can use the class dates or adjust according to your own schedule.

- Jan 31 - Feb 14: Conduct preliminary research and gather resources. Finalize project plan and post to class GitHub.
- Feb 14 - Feb 28: **\_\_**
- Feb 28 - Mar 13: **\_\_**
- Mar 13 - Mar 27: **\_\_**
- Mar 27 - Apr 10: **\_\_**
- Apr 10 - Apr 17: Prepare final presentation.
