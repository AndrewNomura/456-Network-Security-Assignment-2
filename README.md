# Worm*.py

All worm*.py files are educational examples of a worm that could infect a network using a dictionary attack on open ssh ports
Usable on linux only

## Installation

```bash
git clone https://github.com/BachFive/456-Network-Security-Assignment-2.git
```
Choose which worm program to try. worm_kn.py has been tested on at least one VM network.
worm_EC.py should be capable of infecting a machine connected to more than one network

Install chosen worm*.py file to /tmp directory

## Usage

Run as attacker on victims
```bash
python /tmp/worm<version>.py -a
```
or
```bash
python /tmp/worm<version>.py --attack
```

Run as cleaner on victims
```bash
python /tmp/worm<version>.py -c
```
or
```bash
python /tmp/worm<version>.py --clean
```

## License

Copyright 2019 Andrew Nomura, Dustin Vuog, Kevin Nakashima

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Contact Info

Andrew Nomura   drew97.nomura@csu.fullerton.edu

Dustin Vuog     

Kevin Nakashima klnakashima@csu.fullerton.edu
