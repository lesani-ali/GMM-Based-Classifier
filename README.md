# GMM-Based Classifier

This repository contains an implementation of a Gaussian Mixture Model (GMM) based classifier, tested on the MNIST dataset. The project demonstrates the use of GMM for classification tasks and includes custom implementations of the GMM and the classifier.


## Project Structure
```
GMM-based-classifier/
├── classes/                        # Directory containing class implementations
│   ├── __init__.py     
│   ├── GaussianMixture.py          # Gaussian Mixture Model (GMM) implementation
│   ├── GMMBasedClassifier.py       # GMM-based classifier implementation
│   ├── utils.py                    # Utility functions implementation
├── main.ipynb                      # Notebook demonstrating the use of classifier
├── .gitignore                      # Git ignore file
├── environment.yml                 # Python dependencies
└── README.md                       # Project README file
```


## Cloning Repository from GitHub
Use this command to clone the repository from GitHub: <br>
`git clone git@github.com:lesani-ali/GMM-based-classifier.git`<br> 


## Environment Setup
Please follow these steps to set up the working environment:
1. Install Miniconda (use terminal to execute these commands):
    - Create a Directory:<br>
    `mkdir -p ~/miniconda3`
    - Download the Miniconda Installer:<br>
    `curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh`
    - Run the Miniconda Installer:<br>
    `bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3`
    - Remove the Installer Script:<br>
    `rm -rf ~/miniconda3/miniconda.sh`
    - Add to path:<br>
    `source ~/miniconda3/bin/activate`
    - Initialize for bash and zsh shells:<br>
    `~/miniconda3/bin/conda init bash`<br>
    and <br>
    `~/miniconda3/bin/conda init zsh`

    For more information visit [Miniconda](https://docs.anaconda.com/miniconda/) website.

2. Create conda environment and install all packages (I used "data_collection" as a name for my environment): <br>
`conda env create -f environment.yml`

3. Activate the environment: <br>
`conda activate ML`
