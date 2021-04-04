# Assignment 2
The structure of the files belonging to this assignment is as follows:
  - Data: _../../data/assignment2/_  
  - Code: _collocation.py_  
  - Results: _out/_


### Cloning repo and installing dependencies 
To run the script, I recommend cloning this repository and installing relevant dependencies in a virtual ennvironment:

```bash
$ git clone https://github.com/frillecode/CDS-spring-2021-language.git
$ cd CDS-spring-2021-language
$ bash ./create_venv.sh
````
If you run into issues with some libraries/modules not being installed correctly when creating the virtual environment, install these manually by running the following:  
```bash
$ cd CDS-spring-2021-language
$ source frille-lang/bin/activate
$ pip install {module_name}
$ deactivate
```

### Running script
After updating the repo (see above), you can run the .py-file from the command-line by writing the following:
``` bash
$ cd CDS-spring-2021-language
$ source frille-lang/bin/activate
$ cd src/assignment2
$ python3 collocation.py
```