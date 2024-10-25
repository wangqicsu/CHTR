# CHTR

## Introduction




## Installation
Clone this repo and install required packages:
```
git clone https://github.com/wangqicsu/CHTR
pip install -r requirements.txt
```
## dataset

# labels
CHTR needs a .json file for labels.
If you need simple train, please make sure your .json file has the following structure.
```

{
    "image name": "karyotype description",
    "image name": "karyotype description",
    // ...
}

```

If you need 5-fold cross-validation, please make sure your .json file has the following structure.
```

{
  "0": {
    "image name": "karyotype description",
    "image name": "karyotype description",
    // ...
  },
  "1": {
    "image name": "another description",
    "image name": "karyotype description",
    // ...
  }
  // ...
}

```

# images
All images need save a 
## Usage

A easy sample for training for CHTR, please running:
    
    



## Citing KaryoNet


## Contact

