# End to end ML project

### Created a Environment 
```
conda create -p venv python==3.8
conda activate venv/
```

### Insatll all the necessary libraries

```
pip install -r requirements.txt
```
### AWS  beanstalk deployemnet code
```
option_settings:
    "aws:elasticbeanstalk:container:python":
        WSGIPath: application:application
```