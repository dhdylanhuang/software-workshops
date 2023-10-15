# software-workshops

This repository contains the materials for the GU Orbit Software workshop

## Getting Started

### Prerequisites
You need to have anaconda installed for this workshop. You can download it [here](https://www.anaconda.com/download/).\
Alternatively you can use python venv's, but we will not be covering that in this workshop.

### Installing
Clone this repository to your local machine using:
```
git clone <repo link>
```
Then navigate to the directory and create a new conda environment using:
```
conda create -n <env name> python=3.10
```
Activate the environment using:
```
conda activate <env name>
```
Install the required packages using:
```
pip install -r requirements.txt
```
You should now be ready to go!

### Running the notebooks
To run the notebooks:
```
jupyter lab
```
Then select the appropriate file

### For updating the workshops
If you want to update the workshop materials, you can do so by running:
```
git pull
```
