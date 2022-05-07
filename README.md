#### Configure Application Environment
 
Install `virtualenv` for Python:
> may need to upgrade pip if prompted.
 
    $ pip3 install virtualenv
 
Create a virtual environment (in the `backend-api` directory):

    $ python3 -m venv venv

To Activate the Virtual Environment, run the following command

    $ source venv/bin/activate

Download `Django` from Python:
> May need to upgrade pip if prompted. 

    $ pip3 install django

> To confirm it is working correctly, type in the following command.

    $ python3 -m django version

Now install `djangorestframework` from Python using the following command:

    $ pip3 install djangorestframework

Install `djoser` for flask authentication.

    $ pip3 install djoser
    
The next command should handle the previous commands and install other dependencies.

    $ pip3 install -r requirements.txt
