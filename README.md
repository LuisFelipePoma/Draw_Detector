# DevicePredictor


## How to set up the enviroment

- First we create the enviroment `.env`
  ```bash
  python -m venv .env
  ```

- Then install the `requirements.txt`
  ```bash
  pip install -r requirements.txt
  ```

##  How to train the model

- Once you have the enviroment created and the requirements installed, you can run the command `python`
  ```bash
  python addData.py
  ```
  > Then you can add the data to the model
  
- Now for get the dataset you can add to the url the parameter `/prepare`
  > This will save the dataset in `X.npy` and `y.npy` in the folder `model` that you can use to train the model

- Finally run the notebook `model_train` in the folder `model`
  > This will save a file `model.h5` that you can use to predict the device


## How to use

- Once you have the model trained you can run the command `python`
  
  ```bash
  python main.py
  ```
