# εxodus core [![Build Status](https://travis-ci.org/Exodus-Privacy/exodus-core.svg?branch=v1)](https://travis-ci.org/Exodus-Privacy/exodus-core)
Contains:
* Static analysis 
* Network analysis
* Connection helper 

## Installation 
Clone this repository:
```
git clone https://github.com/Exodus-Privacy/exodus-core.git
cd exodus-core
```
Create Python `virtualenv`:
```
virtualenv venv -p python3
source venv/bin/activate
```
Install dependencies:
```
pip install -r requirements.txt
```
Run tests:
```
python -m unittest discover -s exodus_core -p "test_*.py"
```

## Include it to your project
Add the following line in your `requirements.txt`:
```
https://github.com/Exodus-Privacy/exodus-core/releases/download/v1.0.1/exodus_core-1.0.1.tar.gz
```
