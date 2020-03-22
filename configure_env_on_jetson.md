# Configure Virtual Env on Jetson Nano

Python 3.6.9

#### Virtual env:

###### Install virtual envs
`sudo pip install virtualenv virtualenvwrapper`
Config bachrc:
`nano ~/.bashrc`
```
# virtualenv and virtualenvwrapper
export WORKON_HOME=$HOME/.virtualenvs
export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3
source /usr/local/bin/virtualenvwrapper.sh
```
Reload `bashrc` with source:

`source ~/.bashrc`


###### Create virtual env

`mkvirtualenv realsense -p python3`


#### Activate virtual env:
`workon realsense`


### Intall libraries
`pip install numpy`
``
