﻿[<- back](README.md)

# Python venv (PyCharm)
Create venv in a PyCharm project

## Add new venv in the project folder
Choose *Add...* in File / Settings / Project: *Project name* / Project Interpreter:

![](assets/pycharm-add-venv.png)

## Upgrade PIP
In *Terminal* window run: `python -m pip install -U pip`

It will probably fail, so force install with: `python -m pip install -U --force-reinstall pip`

![](assets/pycharm-venv-upgrade-pip.png)

## Install PyQt5, paho-mqtt and unicode

```bash
(venv) D:\Room\rooms\Demo\Applets\Teletroller>pip install PyQt5
Collecting PyQt5
  Downloading https://files.pythonhosted.org/packages/a7/2d/.../PyQt5-5.11.3-5.11.2-cp35.cp36.cp37.cp38-none-win_amd64.whl (93.4MB)

    100% |████████████████████████████████| 93.4MB 262kB/s
Collecting PyQt5_sip<4.20,>=4.19.11 (from PyQt5)
  Downloading https://files.pythonhosted.org/packages/8d/4d/.../PyQt5_sip-4.19.13-cp36-none-win_amd64.whl (51kB)
    100% |████████████████████████████████| 61kB 10.3MB/s
Installing collected packages: PyQt5-sip, PyQt5
Successfully installed PyQt5-5.11.3 PyQt5-sip-4.19.13

(venv) D:\Room\rooms\Demo\Applets\Teletroller>pip install paho-mqtt
Collecting paho-mqtt
  Downloading https://files.pythonhosted.org/packages/25/63/.../paho-mqtt-1.4.0.tar.gz (88kB)
    100% |████████████████████████████████| 92kB 2.5MB/s
Installing collected packages: paho-mqtt
  Running setup.py install for paho-mqtt ... done
Successfully installed paho-mqtt-1.4.0

(venv) D:\Room\rooms\Demo\Applets\Teletroller>pip install unidecode
Collecting unidecode
  Downloading https://files.pythonhosted.org/packages/31/39/.../Unidecode-1.0.23-py2.py3-none-any.whl (237kB)
    100% |████████████████████████████████| 245kB 5.4MB/s
Installing collected packages: unidecode
Successfully installed unidecode-1.0.23
```


## Author

**Marie FAURE** (Sept 30, 2019)
* company: FAURE SYSTEMS SAS
* mail: <a href="mailto:dev@faure.systems" target="_blank">dev@faure.systems</a>
* github: <a href="https://github.com/fauresystems?tab=repositories" target="_blank">fauresystems</a>
* web: 
