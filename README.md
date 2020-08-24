# division_sigma
Determining if a given sentence is positive or negative. Submitted to Ignition Hacks. 

## How I built It
In order to detect whether a given sentence is either positive or negative, I decided to create a sequential neural network using Keras. I chose to work with a classification model. 

I started off with uploading the training data onto my notebook. To filter out noisy data such as words that start with @, quotes, and special characters, I changed the data in the training set. I did the same with the contestant judging file. In tokenization, I converted the sentences into token, which is also known as text segmentation. 
The next step was to prepare and train my model. Like mentioned before, I made my model as sequential. I setted the layers, and I was ready to train. Epochs as 20 and batch size as 32, my model got an accuracy of 79%. 
Lastly, I created the submitting csv file with the id and results.   


## Challenges
My biggest challenge was that I was not completely familiar with building a classification model. I have come across neural networks before, but it wasn’t my best suit. I spent a lot of time researching and getting myself more comfortable with understanding neural networks, and there were multiple times where I was stumped. The only way I could continue to work through was to research and learn.  
A minor challenge was trying to higher the accuracy level, but that was partially solved by raising the epochs number in the model. 

## What's next
What I have created in the two days was a very basic approach to solving this problem. What I can do next is learning a more advanced preprocessing technique, such as data normalization and standardization. I would also find a different way to higher the accuracy, not just relying on the epoch. 
