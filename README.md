# ROBOT-ARM

RobotArm is micro automation tool that enables easy creation and management of development environtments.

## Features
- Easily create development evironment from a yaml file as states
- run management commands easily from any directory in your terminal
- run tests easily from any directory in your terminal
- manage your virtual environments without breaking a sweat

## Future Features
- create ci/cd cycles from yaml files
- use multiple environments
- provision development databases easily

## How to install
> the current versions only runs on ubuntu-20.04
> download latest release
> and run the ./temp_setup script

## Basics
- create a state
> ``arm [-s, --state] create full/path/file_name.yaml``

- activate state
> ``arm [-s, --state] activate state_id``

- run management commands e.g django
>``arm [-c, --command] runserver [defualts to execute command]``
    
-run tests
>``arm [-t, --tests] run [defaults to test discorvery)``

>
> Yaml Config File Template
![yaml_file_template](https://user-images.githubusercontent.com/41565098/161405937-e4ecefe8-738b-434e-9666-4ab98f40be64.jpg)
>

> ### Arm currently only supports only the django web framwork, when using with a framwork...

> this tool is not ready for use, it's not completed and there are several bugs, installation method not concluded yet, to use start the api service, add the dir to path or create an alias to the arm script. user with care.

> To infinity and beyond
> -Buzz Lightyear's
