# sympy-things
## Setup environment for ubuntu 22:04 with python 3.10.12

create virtual environment

    $ python3 -m venv venv
    $ source venv/bin/activate
    $ pip install notebook  

~~~sh

The install command will install a lot of packages in venv: 

$ pip list
Package                   Version
------------------------- --------------
anyio                     4.3.0
argon2-cffi               23.1.0
argon2-cffi-bindings      21.2.0
arrow                     1.3.0
asttokens                 2.4.1
async-lru                 2.0.4
attrs                     23.2.0
Babel                     2.15.0
beautifulsoup4            4.12.3
bleach                    6.1.0
certifi                   2024.2.2
cffi                      1.16.0
charset-normalizer        3.3.2
comm                      0.2.2
debugpy                   1.8.1
decorator                 5.1.1
defusedxml                0.7.1
exceptiongroup            1.2.1
executing                 2.0.1
fastjsonschema            2.19.1
fqdn                      1.5.1
h11                       0.14.0
httpcore                  1.0.5
httpx                     0.27.0
idna                      3.7
ipykernel                 6.29.4
ipython                   8.24.0
isoduration               20.11.0
jedi                      0.19.1
Jinja2                    3.1.4
json5                     0.9.25
jsonpointer               2.4
jsonschema                4.22.0
jsonschema-specifications 2023.12.1
jupyter_client            8.6.1
jupyter_core              5.7.2
jupyter-events            0.10.0
jupyter-lsp               2.2.5
jupyter_server            2.14.0
jupyter_server_terminals  0.5.3
jupyterlab                4.2.0
jupyterlab_pygments       0.3.0
jupyterlab_server         2.27.1
MarkupSafe                2.1.5
matplotlib-inline         0.1.7
mistune                   3.0.2
nbclient                  0.10.0
nbconvert                 7.16.4
nbformat                  5.10.4
nest-asyncio              1.6.0
notebook                  7.2.0
notebook_shim             0.2.4
overrides                 7.7.0
packaging                 24.0
pandocfilters             1.5.1
parso                     0.8.4
pexpect                   4.9.0
pip                       22.0.2
platformdirs              4.2.2
prometheus_client         0.20.0
prompt-toolkit            3.0.43
psutil                    5.9.8
ptyprocess                0.7.0
pure-eval                 0.2.2
pycparser                 2.22
Pygments                  2.18.0
python-dateutil           2.9.0.post0
python-json-logger        2.0.7
PyYAML                    6.0.1
pyzmq                     26.0.3
referencing               0.35.1
requests                  2.31.0
rfc3339-validator         0.1.4
rfc3986-validator         0.1.1
rpds-py                   0.18.1
Send2Trash                1.8.3
setuptools                59.6.0
six                       1.16.0
sniffio                   1.3.1
soupsieve                 2.5
stack-data                0.6.3
terminado                 0.18.1
tinycss2                  1.3.0
tomli                     2.0.1
tornado                   6.4
traitlets                 5.14.3
types-python-dateutil     2.9.0.20240316
typing_extensions         4.11.0
uri-template              1.3.0
urllib3                   2.2.1
wcwidth                   0.2.13
webcolors                 1.13
webencodings              0.5.1
websocket-client          1.8.0
(venv) lg@lg-UX31E:~/misc/gh/sympy-things
~~~