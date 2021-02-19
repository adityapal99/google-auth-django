# google-auth-django

### Clone using
 * git clone -b master https://github.com/adityapal99/google-auth-django.git
 
 
## Steps
##### Step 1: Open the `> front_end/index.html` using Live Server
##### Step 2: Press the `SignIn` Button and `Copy` the `id_token` present in the console after successfully logging in.
> Get the console by pressing `Ctrl + Shift + I` in Chrome
##### Step 3: Running the Python Server
* Run `$ pip install virtualenv` if Windows or Mac otherwise `$ sudo apt install python3-virtualenv` if Linux.
* Create a virtual environment using the command `$ virtualenv venv`. 
* Activate the virtual environment using `> .\venv\Scripts\activate.bat` on Windows or `$ source venv/bin/activate` if Mac or Linux.
* Install all the packages required using `$ pip install -r requirements.txt`.
* Run `$ python manage.py migrate` then `$ python manage.py runserver` to run the server.
