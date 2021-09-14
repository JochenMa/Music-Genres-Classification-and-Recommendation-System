## Music-Genres-Classification-and-Recommendation-System
# Idea
Hello everyone!\
This is my first machine learning project done from zero to finished.\
The idea of our project is to customized music classicfication system and recommendation system.\
We found out that some users who intend to listen niche music are hard to find it in some music platform and also we hope to help the niche music singers increase exposure.\
Lastly, more are more songs have more than one genre and therefore we would like to add on all possible genres to precisely predict user's preference.\

Doesn't it sound exciting??

# Method
Mostly we used a package called librosa, a useful tool which help us analyze audio files and extract the features we wanted.\
Firstly, We downloaded 100-thousand different audio files from Internet but most of them are belongs to Rock genres. We retrained those audio files with less genres data in order to balance our genres.\
Secondly, We put every song muti-labels(not single label) to classify them more specific.\
Third, after finishing data-preprocessing, We Built a model with three layers NN using BinaryCrossentropy as our loss funtion(click the [CODE LINK](https://colab.research.google.com/drive/19vx7-9ogV0VJdORmiBwPiLuU9AnFkrKx?usp=sharing) to see the model detail) which can classify song's genres.(acc up to 75%)
