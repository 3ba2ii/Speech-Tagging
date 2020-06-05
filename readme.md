# Part-of-Speech Tagging 

Part-of-Speech Tagging (POS Tagging) is the process of marking up a word in a text (corpus) as corresponding to a particular part of speech, based on both its definition and its context. In this project we used the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf) that has been able to achieve >97% tag accuracy.
<br />


![POS Tagging](https://i.ibb.co/0nLD1pp/Screen-Shot-2020-06-05-at-2-31-40-AM.png)


<br />

## Description 
 
This model takes an input any sentence or sequence of words and outputs a tag of 12 different tags ('VERB','NOUN','ADV',...) for each word based based on both its definition and its context.

<br />


### Prerequisites

This project uses [opencv](https://pypi.org/project/opencv-python/) and [PyTorch](https://pytorch.org/docs/stable/index.html) to install these libraries.

##### Install OpenCv :
```bash
pip install opencv-python
```
##### Install PyTorch :
```bash
pip3 install torch torchvision
```
<br />



## Authors

- **Ahmed Abd-Elbakey Ghonem** - [**Github**](https://github.com/3ba2ii)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.





