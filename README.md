# retailBanking-demo
### Built With

* [Bootsrap](https://getbootstrap.com/)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)

<!-- GETTING STARTED -->
## Getting Started

Follow the installation steps to open project without error

### Installation
 
1. Download and extract the project
2. I'm using xampp, so you can also use it and Create the database
3. Upload or Import flask.sql in your database. 
4. Download python 3.x and install on your PC. My pc is 64bit so i installed Python3(64bit). Set environmental variable for both python and pip or else you get command not found.
5. I've used virtual environment. It's not necessary, but using virtual environment is preferable.  
Note: You can skip the 5th step if you don't want virtual environment  
(i) Make sure you've set your python path in environmental variable and then install 
```sh

python -m venv venv

```
(ii) I've already created. So now you want to activate it. I'm using windows. so I used CMD. Now open the cmd of your current project folder. My project folder is newsland.
```sh

D:\tcsdemo> cd /venv/Scripts/activate

After venv is activated

(venv) D:\tcsdemo>

```
(iii) Once you can close the project, this command is user to open the venv again and for deactivation command also given.
```sh

D:\tcsdemo>workon venv

If not working again activate your venv

(venv) D:\tcsdemo>

For Deactivating,

D:\tcsdemo> cd /venv/Scripts/deactivate

```
6. Install the following requirements by following command.
```sh

D:\tcsdemo> pip install -r requirements.txt

```
7. To run the the code, use this command 
```sh

D:\tcsdemo>python app.py

or

D:\tcsdemo>flask run

```

8. If you get any error, make sure you've done following things 
```sh

1. Python version should be 3.x.
2. Settingup Environment variables.
3. Installed all requirements without errors.
4. I am using 64 bit. If you are using 32 Bit google it and fix it.
5. Check the server is active or not.
6. Imported sql file.
7. Everything is done.
```

9. Admin Login.
```sh
url : http://127.0.0.1:5000/login
Username => admin,
Password => Admin@2020,

```
