# Face-Login System 

This is a web based facial log in/ Sign up website which uses Facial recognition for user authentication and this can be integrated with various websites or web applications.

   This Project is based on [**FaceNet**](https://arxiv.org/abs/1503.03832) deep learning model and uses [**Flask**](https://palletsprojects.com/p/flask/) server for running the [**Keras**](https://www.tensorflow.org/api_docs/python/tf/keras) neural network model, and [**MongoDB**](https://www.mongodb.com/) used as database.
   
   
## Setting up Tools and Libraries
  * [Install Python](https://realpython.com/installing-python/)
  * set up  [Mongodb Atlas](https://www.knowi.com/blog/getting-started-with-mongodb-atlas-overview-and-tutorial/) / [Install and configure MongoDB](https://medium.com/@LondonAppBrewery/how-to-download-install-mongodb-on-windows-4ee4b3493514)

For running this project, we need to clone this repository and open in text editor ( vs code prefered )  
we will be using seperate separate [**Virtual Python Environment**](https://developer.akamai.com/blog/2017/06/21/how-building-virtual-python-environment) for this project and required libraries will be installed in this environment only, using **requirements.txt** file. Dependencies can be installed using  `pip install requirements.txt` 

In **app.py** file, flask_secrete **app.secret_key** (random binary string) and  unique  **MongoURI** (to connect to database) are used.
 After all configuration is done, project can be run using `python wsgi.py` which will run project on localhost:5000 

# To Run the project:

## step 1 : 
  Clone this repo
 
## step 2 :  
In root directry create `.env` file containg <br>
```  
  FLASK_SECRET=''
  MONGO_URI='mongodb+srv://'
```    
  
## step 3 : 
  Run `setup_venv.bat` file to create virtual environment and install required libraries<br>
  ```
    setup_venv.bat
  ```  
  or <br/>
  ```
  manually create virtual enviroment using "python -m venv venv"
  and download required libraries by "pip install -m requirements.txt"
  ```
## step 4 : 
  Start project using batchfile
  in `cmd` 

open Command Prompt and run 

    run
or
    
    python wsgi.py
  
 this will run your project on localhost:5000  
 #### Now go to your browser and load http://localhost:5000/ 
 ##### That’s it, You have successfully run this project on your machine.
   <br>
   <br>
   <br>
 
 
 

