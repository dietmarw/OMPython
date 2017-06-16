# OMPython

OMPython is a Python interface that uses CORBA (omniORB) or ZeroMQ to communicate with OpenModelica.

## Dependencies

- omniORB/PyZMQ is required.
- omniORB is installed including Python support (the omniidl command needs to be on the PATH)  
  On Ubuntu, this is done by running `sudo apt-get install omniorb python-omniorb omniidl omniidl-python`
- Python 2.7 is required (omniORB restriction). Download python from http://www.python.org/download/
- pip is recommended.

## Installation

### Linux
```bash
$ pip install https://github.com/OpenModelica/OMPython/archive/master.zip
```

### Windows
- Add python to your PATH.
- Start command prompt/terminal and execute commands,
```powershell
> cd \pathtoOpenModelica\share\omc\scripts\PythonInterface
> pip install .
```
- This will add OMPython to the python 3rd party libraries.

## Usage

```python
import OMPython
help(OMPython)
```

## Contact
Adeel, adeel.asghar@liu.se
Anand, ganan642@student.liu.se
