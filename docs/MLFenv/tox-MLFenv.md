```shell
MLFenv36 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/algotrade/ML_Finance/.tox/MLFenv36
MLFenv36 installdeps: -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/algotrade/ML_Finance/requirements.txt
MLFenv36 installed: anyio==3.4.0,argon2-cffi==21.1.0,async-generator==1.10,attrs==21.2.0,Babel==2.9.1,backcall==0.2.0,bleach==4.1.0,certifi==2021.10.8,cffi==1.15.0,charset-normalizer==2.0.8,contextvars==2.4,cycler==0.11.0,dataclasses==0.8,decorator==5.1.0,defusedxml==0.7.1,entrypoints==0.3,idna==3.3,immutables==0.16,importlib-metadata==4.8.2,ipykernel==5.5.6,ipython==7.16.2,ipython-genutils==0.2.0,jedi==0.17.2,Jinja2==3.0.3,json5==0.9.6,jsonschema==3.2.0,jupyter-client==7.1.0,jupyter-core==4.9.1,jupyter-server==1.12.1,jupyterlab==3.2.4,jupyterlab-pygments==0.1.2,jupyterlab-server==2.8.2,kiwisolver==1.3.1,MarkupSafe==2.0.1,matplotlib==3.3.4,mistune==0.8.4,nbclassic==0.3.4,nbclient==0.5.9,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,notebook==6.4.6,numpy==1.19.5,packaging==21.3,pandas==1.1.5,pandocfilters==1.5.0,parso==0.7.1,pexpect==4.8.0,pickleshare==0.7.5,Pillow==8.4.0,plotly==5.4.0,prometheus-client==0.12.0,prompt-toolkit==3.0.23,ptyprocess==0.7.0,pycparser==2.21,Pygments==2.10.0,pyparsing==3.0.6,pyrsistent==0.18.0,python-dateutil==2.8.2,pytz==2021.3,pyzmq==22.3.0,requests==2.26.0,scipy==1.5.4,seaborn==0.11.2,Send2Trash==1.8.0,six==1.16.0,sniffio==1.2.0,tenacity==8.0.1,terminado==0.12.1,testpath==0.5.0,tornado==6.1,traitlets==4.3.3,typing_extensions==4.0.1,urllib3==1.26.7,wcwidth==0.2.5,webencodings==0.5.1,websocket-client==1.2.1,zipp==3.6.0
MLFenv36 run-test-pre: PYTHONHASHSEED='672128589'
MLFenv36 run-test: commands[0] | python -c 'print((80*"=")+"\n"+"python3.6_testenv:MLFenv"+"\n"+(80*"="))'
================================================================================
python3.6_testenv:MLFenv
================================================================================
MLFenv36 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip install --upgrade pip setuptools wheel"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip install --upgrade pip setuptools wheel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
MLFenv36 run-test: commands[2] | pip install --upgrade pip
Requirement already satisfied: pip in ./.tox/MLFenv36/lib/python3.6/site-packages (21.3.1)
MLFenv36 run-test: commands[3] | pip install --upgrade setuptools
Requirement already satisfied: setuptools in ./.tox/MLFenv36/lib/python3.6/site-packages (58.3.0)
Collecting setuptools
  Using cached setuptools-59.4.0-py3-none-any.whl (952 kB)
Installing collected packages: setuptools
  Attempting uninstall: setuptools
    Found existing installation: setuptools 58.3.0
    Uninstalling setuptools-58.3.0:
      Successfully uninstalled setuptools-58.3.0
Successfully installed setuptools-59.4.0
MLFenv36 run-test: commands[4] | pip install --upgrade wheel
Requirement already satisfied: wheel in ./.tox/MLFenv36/lib/python3.6/site-packages (0.37.0)
MLFenv36 run-test: commands[5] | python -c 'print((80*"~")+"\n"+"python -m pip list --format=columns"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
python -m pip list --format=columns
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
MLFenv36 run-test: commands[6] | python -m pip list --format=columns
Package             Version
------------------- ---------
anyio               3.4.0
argon2-cffi         21.1.0
async-generator     1.10
attrs               21.2.0
Babel               2.9.1
backcall            0.2.0
bleach              4.1.0
certifi             2021.10.8
cffi                1.15.0
charset-normalizer  2.0.8
contextvars         2.4
cycler              0.11.0
dataclasses         0.8
decorator           5.1.0
defusedxml          0.7.1
entrypoints         0.3
idna                3.3
immutables          0.16
importlib-metadata  4.8.2
ipykernel           5.5.6
ipython             7.16.2
ipython-genutils    0.2.0
jedi                0.17.2
Jinja2              3.0.3
json5               0.9.6
jsonschema          3.2.0
jupyter-client      7.1.0
jupyter-core        4.9.1
jupyter-server      1.12.1
jupyterlab          3.2.4
jupyterlab-pygments 0.1.2
jupyterlab-server   2.8.2
kiwisolver          1.3.1
MarkupSafe          2.0.1
matplotlib          3.3.4
mistune             0.8.4
nbclassic           0.3.4
nbclient            0.5.9
nbconvert           6.0.7
nbformat            5.1.3
nest-asyncio        1.5.1
notebook            6.4.6
numpy               1.19.5
packaging           21.3
pandas              1.1.5
pandocfilters       1.5.0
parso               0.7.1
pexpect             4.8.0
pickleshare         0.7.5
Pillow              8.4.0
pip                 21.3.1
plotly              5.4.0
prometheus-client   0.12.0
prompt-toolkit      3.0.23
ptyprocess          0.7.0
pycparser           2.21
Pygments            2.10.0
pyparsing           3.0.6
pyrsistent          0.18.0
python-dateutil     2.8.2
pytz                2021.3
pyzmq               22.3.0
requests            2.26.0
scipy               1.5.4
seaborn             0.11.2
Send2Trash          1.8.0
setuptools          59.4.0
six                 1.16.0
sniffio             1.2.0
tenacity            8.0.1
terminado           0.12.1
testpath            0.5.0
tornado             6.1
traitlets           4.3.3
typing_extensions   4.0.1
urllib3             1.26.7
wcwidth             0.2.5
webencodings        0.5.1
websocket-client    1.2.1
wheel               0.37.0
zipp                3.6.0
MLFenv36 run-test: commands[7] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
MLFenv36 run-test: commands[8] | pip freeze
anyio==3.4.0
argon2-cffi==21.1.0
async-generator==1.10
attrs==21.2.0
Babel==2.9.1
backcall==0.2.0
bleach==4.1.0
certifi==2021.10.8
cffi==1.15.0
charset-normalizer==2.0.8
contextvars==2.4
cycler==0.11.0
dataclasses==0.8
decorator==5.1.0
defusedxml==0.7.1
entrypoints==0.3
idna==3.3
immutables==0.16
importlib-metadata==4.8.2
ipykernel==5.5.6
ipython==7.16.2
ipython-genutils==0.2.0
jedi==0.17.2
Jinja2==3.0.3
json5==0.9.6
jsonschema==3.2.0
jupyter-client==7.1.0
jupyter-core==4.9.1
jupyter-server==1.12.1
jupyterlab==3.2.4
jupyterlab-pygments==0.1.2
jupyterlab-server==2.8.2
kiwisolver==1.3.1
MarkupSafe==2.0.1
matplotlib==3.3.4
mistune==0.8.4
nbclassic==0.3.4
nbclient==0.5.9
nbconvert==6.0.7
nbformat==5.1.3
nest-asyncio==1.5.1
notebook==6.4.6
numpy==1.19.5
packaging==21.3
pandas==1.1.5
pandocfilters==1.5.0
parso==0.7.1
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.4.0
plotly==5.4.0
prometheus-client==0.12.0
prompt-toolkit==3.0.23
ptyprocess==0.7.0
pycparser==2.21
Pygments==2.10.0
pyparsing==3.0.6
pyrsistent==0.18.0
python-dateutil==2.8.2
pytz==2021.3
pyzmq==22.3.0
requests==2.26.0
scipy==1.5.4
seaborn==0.11.2
Send2Trash==1.8.0
six==1.16.0
sniffio==1.2.0
tenacity==8.0.1
terminado==0.12.1
testpath==0.5.0
tornado==6.1
traitlets==4.3.3
typing_extensions==4.0.1
urllib3==1.26.7
wcwidth==0.2.5
webencodings==0.5.1
websocket-client==1.2.1
zipp==3.6.0
MLFenv36 run-test: commands[9] | python -c 'print((80*"~")+"\n"+"End-of-Commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
End-of-Commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
MLFenv37 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/algotrade/ML_Finance/.tox/MLFenv37
SKIPPED: InterpreterNotFound: 
MLFenv38 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/algotrade/ML_Finance/.tox/MLFenv38
SKIPPED: InterpreterNotFound: 
MLFenv39 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/algotrade/ML_Finance/.tox/MLFenv39
SKIPPED: InterpreterNotFound: 
___________________________________ summary ____________________________________
  MLFenv36: commands succeeded
SKIPPED:  MLFenv37: InterpreterNotFound: 
SKIPPED:  MLFenv38: InterpreterNotFound: 
SKIPPED:  MLFenv39: InterpreterNotFound: 
  congratulations :)
```