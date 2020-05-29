# Music-Generation
This is a music generator in which a user can select a particular genre like - Classical, Jazz, Pop, Rock etc and can generate the music midi file format.

So, in this project I have used 2 different algorithm - 

(i)  LSTM Seq2Seq model.
(ii) RBM(Restricted Boltzman Machine) algorithm.

So, lets discuss below methods for running both the projects -

1) LSTM-Music Generation :-

## Requirements- 

Required Packages:

pip install tensorflow
pip install keras
pip install mido
pip install sklearn
pip install numpy
pip install ipykernel
pip install matplotlib

Dataset:

In this project i have downloaded midi format songs of various genres - Classical, Jazz, Rock, Pop etc


Train the Network:

For training the network select a particular genre kept in category folder and then run the trained.ipynb file

Generation of Music:

The generated midi songs will be saved in Music_Genrated folder and to achieve that just run Generation.ipynb file.


