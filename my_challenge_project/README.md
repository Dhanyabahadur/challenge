# Convolutional Neural Network for style transfer

## Setup
1.Install Python(2.7), pip and virtualenv on your machine.

2.After having the setup, clone a copy the repository:

```
git clone https://github.com/Dhanyabahadur/challenge.git
```

3.Then you navigate to this folder in terminal and install requirements needed for Jupyter notebooks.
  ```
  cd my_challenge_project
  virtualenv venv
  source venv/bin/activate
  pip install -r requirements.txt
  
 ```
 4. If it doesn't exist , create a file called `~/.keras/keras.json` and make sure it looks like the following:
 
   ```
   
{
       "image_dim_ordering": "tf",
       "epsilon": 1e-07,
       "floatx": "float32",
       "backend": "tensorflow"
}

   ```
 
5.Now you can start Jupyter and Browse, open , run and modify the notebooks.

```
   jupyter notebook
   
```

