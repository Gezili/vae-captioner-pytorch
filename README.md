# vae-captioner-pytorch

Implementation of an image captioner using a VAE. Currently has a training script.

To train, create the following directories - will add script to do so in the future.

├── ...
├── data                    
│   ├── Coco - All downloads can be found on https://cocodataset.org/#download
│   |   ├──annotations
|   |   |   └──captions-val2017.json #Unzip from 2017 Train/Val annotations [241MB] from COCO 
|   |   └──images
|   |       ├──000000000139.jpg   #Unzip from 2017 Val images [5K/1GB]
|   |       └── ...
│   └── glove.6B.50d.txt         #Download from https://nlp.stanford.edu/projects/glove/
└── ...
