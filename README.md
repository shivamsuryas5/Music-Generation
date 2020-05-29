# Music-Generation
This is a music generator in which a user can select a particular genre like - Classical, Jazz, Pop, Rock etc and can generate the music midi file format.

So, in this project I have used 2 different algorithm - 

(i)  LSTM Seq2Seq model.
(ii) RBM(Restricted Boltzman Machine) algorithm.

So, lets discuss below methods for running both the projects -

# 1) LSTM-Music Generation :-

## Requirements- 

### Required Packages:

pip install tensorflow </br>
pip install keras </br>
pip install mido </br>
pip install sklearn </br>
pip install numpy </br>
pip install ipykernel </br>
pip install matplotlib </br>

## Dataset:

In this project i have downloaded midi format songs of various genres - Classical, Jazz, Rock, Pop etc


## Train the Network:

For training the network select a particular genre kept in category folder and then run the **trained.ipynb** file

## Generation of Music:

The generated midi songs will be saved in Music_Genrated folder and to achieve that just run **Generation.ipynb** file.


# 2) RBM Music Generation

## Requirements

Tensorflow </br>
pandas </br>
numpy </br>
msgpack-python </br>
glob2 </br>
tqdm </br>
python-midi </br>


## Dataset:

In this project i have downloaded midi format songs of various genres - Classical, Jazz, Rock, Pop etc

## Generation of Music:

The generated midi songs will be saved in Music_Genrated folder and to achieve that just run **Generation.ipynb** file.

No need for training because in side **Generation.ipynb** file itself the selected music genre will be automatically processed and the desired music will be generated in the sequence of multiple midi file format which in turn must be converted to mp3 by the help of this  website https://audio.online-convert.com/convert/midi-to-mp3 and after that each mp3 sequence must be combined into a single file through this website https://audio-joiner.com/








