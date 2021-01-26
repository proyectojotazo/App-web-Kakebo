# Web app Kakebo

## STEPS FOR START

- Clone the repository in a new folder:

  > C:/new_folder> `git clone https://github.com/proyectojotazo/App-web-Kakebo.git`

- Create a virtual environment

  > C:/new_folder/*your_folder*> `python -m venv your_virtual_environment`

  - The hierarchy of the folders will be like this:

    ```
    new_folder
    │   
    └───miAPP
        │   
        └───movements
        │
        └───your_virtual_environment       
    
    ```
- Activate your virtual environment

  - WINDOWS:
  
    `your_virtual_environment\Scripts\activate`

  - MAC o LINUX:
  
    `. your_virtual_environment/bin/activate`

    >If your virtual environment is activated you can see ***(your_virtual_environment) C:/...*** in your terminal

- When the VE is activated we have to install **requirements.txt**

  `pip install -r requirements.txt`

- Last step, we must to rename the file **config_template.py** to **config.py** and fill the **SECRET_KEY** with a secret key 
and **DB_FILE** with a path where we want to create the database file