# flask-Project
Blog site written in flask, persistence using SqLite 



## Getting Started: Windows Setup using powershell

* Set the virtual environment (needs python3)


      pip install virtualenv 

      python3 -m venv ./env         //create the virtual env on ./env

      cd \env\Scripts               //Look for the activate command

      ./Activate.ps1                //Activate the venv

* Set env variables on flask-Project dir

      $env:FLASK_APP='flaskr'
  
      $env:FLASK_DEV=development
      
* Start DB and run flask

      flask init-db
      flask run
