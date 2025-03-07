# Official Django Tutorial 5.1



## Description

 [Official Django Tutorial](https://docs.djangoproject.com/en/5.1/intro/tutorial01/)

## Getting Started

### Dependencies

* This code is a Django web application and requires:
  - Python >= 3.13   
  - Django >=5.1    

The remaining dependencies can be found in `pyproject.toml`
  

### Run this project locally

* Navigate to a working directory
```
git clone git@github.com:diek/djangotutorial5.1.git  

cd like-counter  
```
* create a virtualenv, activate it, and install requirements  
```
python3 -m venv _env  
source _env/bin/activate  
(_env)$ python3 -m pip install --upgrade pip  
(_env)$ python3 -m pip install -r requirements  
```
* create a superuser to login
```
(_env)$ ./manage createsuperuser
```

### Import Some Data to work with
```
./manage.py loaddata question.json  
./manage.py loaddata choice.json    
```

### Executing program

* How to run the program
```
python manage.py runserver   
```

### Testing
Disable Django-Debug Toolbar before running tests. References are found in:
- settings.py
- urls.py

## Authors

[Derrick Kearney](mailto:d_kearney@bellaliant.net)  


## Version History

* 0.1
    * Initial Release  

## License

This project is licensed under the MIT License - see the LICENSE.md file for details  
