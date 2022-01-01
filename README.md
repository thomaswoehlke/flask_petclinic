# flask_petclinic

## dev environment

### git
* Version 0.0.1
* [https://github.com/thomaswoehlke/flask_petclinic.git](https://github.com/thomaswoehlke/flask_petclinic.git)

````bash
    git clone git@github.com:thomaswoehlke/flask_petclinic.git
````

### setup

````bash
    make venv
    . ./venv/bin/activate
    make start
    ./run.sh
````

### run testserver

````bash
    . ./venv/bin/activate
    ./run.sh
````

### update dependencies

````bash
    . ./venv/bin/activate
    make update
 ````

### change configuration

````bash
    vim project/config/config.py
    vim project/config/database.py
    vim requirements/in/build.in
    make start
````

### change dependencies

````bash
    . ./venv/bin/activate
    vim requirements/in/build.in
    vim requirements/in/docs.in
    vim requirements/in/tests.in
    vim requirements/in/typing.in
    vim requirements/in/dev.in
    vim requirements/in/linux.in
    vim requirements/in/windows.in
    make update
````

## UML

### Domain Class Modell

![Domain_Class_Modell](docs/uml/Domain_Class_Modell.png)

### Use Cases

![use_cases_all](docs/uml/use_cases.png)
