# **Blog-app**
### A basic blog app using flask
--------------------------
## Setup instructions
--------------------------
### **Server**
* **Step 1 (optional but recommended)**

    Create a python virtual environment by using virtualenv or conda
    
        conda create -n environment python3.6

    or

        python -m venv environment && source environment/bin/activate
* **Step 2**

    Clone this repo
    
        git clone https://github.com/Harendra8095/blog-app.git && cd blog-app

* **Step 3**

    Install the dependencies
        
        pip install -r requirements.txt
* **Step 4**

    Create the following environment variables
    
        export FLASK_APP=flaskr
        export FLASK_ENV=development
* **Step 5**

    To generate the database
    
        flask init-db
* **Step 6**

    To run the server
    
        flask run

## **Use app in browser**

    Go to the address your console show

        * Running on <Address>
