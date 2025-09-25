# MS17-010 Exploit Code

This is some no-bs public exploit code that performs SecretsDump over the established SMB session.

Included is also an enternal blue checker script that allows you to test if your target is potentially vulnerable to MS17-010

run `python eternal_checker.py <TARGET-IP>`


# Requirements
Core exploit code requires impacket and the `mysmb.py` library (included with the repo). To install any requirements simply use pip on the `requirements.txt` file. It's always recommended you use a virtual environment like `venv` when installing python dependencies, but use whatever you like.

#### IMPORTANT SUPPORT INFO:

## Python3
`pip install -r requirements.txt`

## USAGE:

`python zzz_exploit.py <login>:<password>@<TARGET-IP>`

has been tested on Windows 2003, Windows 7
