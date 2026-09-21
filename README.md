# Hollywood Celebrity Fake Face Generation Using Generative Adversial Network(GAN).
A Generative Adversarial Network (GAN) is a machine learning framework where two neural networks compete against each other to create realistic synthetic data.
<img width="850" height="371" alt="GAN_architecture2" src="https://github.com/user-attachments/assets/b64a4b95-b7ac-4989-8698-8dbc5b3f09f9" />
**The Generator:** This network takes random noise as input and transforms it into new, synthetic data (like an image or audio). Its goal is to fool the discriminator. 
**The Discriminator:** This network acts as a binary classifier. It receives both real data from a training set and fake data from the generator. Its job is to tell which data is real and which is fake. 
The Adversarial Game: The two models improve together through competition. As the generator gets better at making fakes, the discriminator gets better at spotting them. 
In this project, Fake face images of Hollywood actors and actresses (close to Real Images) were generated using 
Generator Model of Generative Adversial Network. Then the Discriminator was asked to distinguish these Fake Images 
from Real Images Images of Hollywood actors and actress which the Discriminator failed to recognise and suggested 
these Fake Images to be Real Images.
Some Real Face Images of one of the Celebrity (i.e Brad Pitt) from the Celebrity Dataset (Source:Kaggle) using
which the Deep Convolutional Generative Adversial Network was trained on. \
<img width="2344" height="2330" alt="Brad_Pitt_Training_Images" src="https://github.com/user-attachments/assets/eb580abd-a80c-4e75-82c9-583743036841" />


## Dataset Description:
This dataset (Source:Kaggle) contains images of 18 Hollywood celebrities with 100 images of each celebrity. The people in this dataset are:

1. Angelina Jolie
2. Brad Pitt
3. Denzel Washington
4. Hugh Jackman
5. Jennifer Lawrence
6. Johnny Depp
7. Kate Winslet
8. Leonardo DiCaprio
9. Megan Fox
10. Natalie Portman
11. Nicole Kidman
12. Robert Downey Jr.
13. Sandra Bullock
14. Scarlett Johansson
15. Tom Cruise
16. Tom Hanks
17. Will Smith

Then Deep Convolutional Generative Adversial Network used for training the Generator and Discriminator Model and the network was trained for 100 epochs and the results were as follows.
## Results
Some Fake Hollywood Celebrity Face Images(For instance one of the Celebrity i.e Brad Pitt) generated using Deep Convolutional Generative Adversial Network were as follows:
The accuracy obtained on Real Hollywood Celebrity Face Images was _______ and the accuracy obtained on Fake 
Hollywood Celebrity Face Images was _____________ and the Discriminator Accuracy obtained was _________ after
training the network for 100 epochs.
The training and validation losses obtained were as follows:
