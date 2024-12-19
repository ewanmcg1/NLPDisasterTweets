# NLPDisasterTweets
Attempting to produce the best possible score on the NLP With Disaster Tweets Kaggle Competition.
This was for my Aritificial Intelligence course in my Masters in CS program At UTK.

By following the sample code, my initial run returned a rather high accuracy of
0.83634. This initial run used an Adam optimizer, a learning rate of 1e-5, 2 epochs, and a
batch size of 32. Initially, I decided to alter these hyperparameters in hopes of slightly
tweaking the model for better performance. After another 8 tries and a lot of trial and error,
I was unfortunately never able to better the initial run. The second-best run, which has
been included in this repository gave an accuracy of 0.83604, falling just short of the base
run. This submission used an AdamW optimizer, a learning rate of 3e-5, 2 epochs and a
batch size of 32. My other runs which tinkered with hyperparameters returned accuracies
of 0.82041, 0.83083, 0.83236, 0.82837, 0.83174, 0.83328, and 0.82715.
I then decided that perhaps changing the model may be the better alternative,
and attempted to use other KerasNLP library models such as the Albert model. This model,
paired with the best hyperparameters from the previous runs returned only an accuracy of
0.73735. The code for this is also attached in the zip file and labeled Albert model. I also
attempted Albert large and extra large models but had no luck matching the initial
accuracy. Overall, it was disappointing to not be able to surpass the starting code, but was
a learning experience.
