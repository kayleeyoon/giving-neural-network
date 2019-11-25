# neural-networks
Using contact information in Salesforce such as relationship to the college, past giving, event attendance, 
contact reports, and many more features, I was able to predict how much someone would give to my college in the next year. 

My most successful model achieved at 94% test accuracy after 1,000 training epochs.  It had 74 inputs, 3 hidden layers (each with 40 nodes), and 12 output classifications (each classification represented a giving class (0-200, 201-1000, 1001-2500, and so on).

I then made a model that didn't rely on past giving information and had only 4 output classifications.  This choice was made because it will help identify the potential of new contacts who haven't given before.  It achieved an 89.4% test accuracy after 1,500 training epochs.  It had 38 inputs, 3 hidden layers (each with 40 nodes) and 4 output classifications (0-1000, 1001-5000, 5001-50000, and 50000+).

In order to have a better understanding of the math behind neural networks, I decided not to use any machine learning libraries.
I started with a basic XOR neural network, then worked on a neural network that classified emails as spam or not spam.  

Once I had a good understanding of neural networks, I began my real challenge of using the real data from my college to predict 
donor giving.  Once I built by base model, I tested using more layers to find the optimal network for my task.

The bulk of my work was on understanding backpropagation as well as how to transform the data into values the network could learn on.
