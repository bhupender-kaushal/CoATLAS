# CoATLAS
Official repository for "CoATLAS: A generalisable Self-Supervised framework using Triple Attention
Mechanism for Robust Vessel Segmentation Across Domains"


## Overview of the proposed method*

<div align="center">
  <img src="fig/allnew_fig.png" width="80%" alt="CoATLAS Framework" style="border:1px solid black;">
  <p>Overview of the CoATLAS Framework</p>
</div>




## Requirements
  * OS : Ubuntu
  * Python >= 3.9
  * PyTorch >= 1.12.1

## Setup Environment
*Create a conda environment and then do pip install -r requirements.txt*




## Data
In our experiments, we used the publicly available XCAD dataset, available [[here](https://www.dropbox.com/scl/fi/mvstwdgxo0hfk678x94d4/XCAD.zip?rlkey=qdztml0gzfzoc0t5d16k71u76&e=1&dl=0)]

## Training
```
python3 main.py -p train -c config/train.json
```
## Test

```
python3 main.py -p test -c config/test.json
```

## Pre-trained Models
We are uploading the pretrained models for evaluations at your premise......

 <!-- You can download our pre-trained model of the XCAD dataset [here](https://drive.google.com/file/d/180xRhnpAsT6ZrM-FrMTZ6AVkqnfBBqYm/view?usp=sharing).
Then, you can test the model by saving the pre-trained weights in the directory ./experiments/pretrained_model.
To briefly test our method given the pre-trained model, we provided the toy example in the directory './data/'. -->

## Citations
```


```