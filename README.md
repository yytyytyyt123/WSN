# WSN
WeatherScaleNet

## Requirements
- torch==1.11.0
- timm==1.0.12
- scikit_learn==1.0.2
- tqdm==4.67.1
- pandas==1.4.1
- numpy==1.22.3

## Folder Structure

```tex
└── code-and-data
    ├── config                 # Including detail configurations
    ├── cpt                    # Storing pre-trained weight files (manually create the folder and download files)
    ├── data                   # Including traffic data (download), adj files (generated), and the meta data
    ├── lib
    │   |──  utils.py          # Codes of preprocessing datasets and calculating metrics
    ├── log                    # Storing log files
    ├── model
    │   |──  models.py         # The core source code of our PatchSTG
    ├── main.py                # This is the main file for training and testing
    └── README.md              # This document
```

## Datasets
python main.py --config ./config/wind.conf



