# Regression with a Flood Prediction Dataset

https://www.kaggle.com/competitions/playground-series-s4e5/data


- To create env folder for conda:
```conda create --prefix ./env```

- To download requirements from a environment.yml file and create a ./env file:
```conda env create --prefix ./env --file environment.yml```

- To create environment.yml file for conda:
```conda env export > environment.yml```

- To run the conda environment:
```conda activate ./env```

- To start the jupyter notebook:
```jupyter notebook```

## Getting Started
- Create a conda environment based off of ```environment.yml``` using: 
```conda env create --prefix ./env --file environment.yml```
- Run ```get_data.ipynb``` to unzip the zipfile contents into the data directory
- Run ```flood_prediction.ipynb``` to train the model