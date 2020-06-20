# Part-of-Speech Tagging 

Part-of-Speech Tagging ```POS Tagging``` is the process of marking up a word in a text ```corpus``` as corresponding to a particular part of speech, based on both its definition and its context. In this project we developed a Hidden Markov Model (HMM) to build the model.

![POS Tagging](/_post-hmm.png)


<br />

## Description
 
This model takes an input any sentence or sequence of words and pre-process it before passing it to the HMM then outputs a probability of each word to what tag on it outputs a tag of 12 different tags ('VERB','NOUN','ADV',...) for each word based on both its definition and its context.


## Content

- [Part-of-Speech Tagging](#part-of-speech-tagging)
  - [Description](#description)
  - [Content](#content)
  - [Dataset](#dataset)
  - [Install Prerequisites](#install-prerequisites)
  - [Authors](#authors)
  - [Contributing](#contributing)

## Dataset 

In this project we used the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf).

![part of the dataset](https://i.ibb.co/XFv2J1G/Screen-Shot-2020-06-20-at-6-12-00-PM.png)
<br />

## Install Prerequisites
This project requires **Python 3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
   ```bash
    $pip install numpy
   ```
- [Pandas](https://pandas.pydata.org/)
  ```bash
    $conda install pandas
   ```
- [Matplotlip](https://matplotlib.org/)
  ```bash
    $pip install -U matplotlib
   ```
- [NTLK](https://www.nltk.org/)
    ```bash
      $pip install --user -U nltk
    ```


## Authors

- **Ahmed Abd-Elbakey Ghonem** - [**Github**](https://github.com/3ba2ii)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.





