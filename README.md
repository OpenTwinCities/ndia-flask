ndia-flask
==========

Northside Digital Innovation Alliance project prototype

#Dependencies

##Python

Make sure you have Python on your computer. The following two commands should work:

```
python --version
pip --version
```


##virtualenv

[Virtualenv](https://virtualenv.readthedocs.org/en/latest/) makes it possible to install multiple Python environments on one computer; including installing a Python environment just for this project. 

[Flask installation with virtualenv notes](http://flask.pocoo.org/docs/0.10/installation/#virtualenv)

### Install

```
pip install virtualenv
pip install virtualenvwrapper
```

# Get Northside Digital Assets System

```
git clone https://github.com/OpenTwinCities/ndia-flask.git
cd ndia-flask
virtualenv env
```

# Run Northside Digital Assets System

```
cd ndia-flask
source env/bin/activate
pip install -r requirements.txt
```


#Resources

[The Flask Mega Tutorial](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
