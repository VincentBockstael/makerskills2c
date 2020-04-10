# Maker Skills: Mouse Violin 

Musical expression is a bottleneck for imitating an acoustic isntruments with digital synthesis. Apart from fluid dynamics and pitchbends, we are missing out on the instrument dependent characteristics. Such as the expression caused by breath and pressure in a clarinet or the bowing position and velocity in a violin. The combination of persueing these instrument dependent characteristics and defining a framework for expression might just be the solution achieve a realistic imitation of acoustic instruments. This is exactly what we aim to do here. This project explores the possibility of musical expression of a digital violin through the use of a simple object like a computer mouse. 

Software instruments that imitate acoustic instruments have been around for a while now. Altough the research on physical modeling of instruments stretches far beyond musical applicability, some interesting vsts, libraries and tools have been developed to put to use these ideas. One of those libraries is [The Synthesis ToolKit in C++ (STK)](https://ccrma.stanford.edu/software/stk/ "The Synthesis ToolKit in C++ (STK)"). For an in depth overview of how this physical modelling works, it is highly recommended to browse through the STK website and source code.

## Installation

### Installing Python, PIP, and libraries:

Python is an interpreted, high-level, general-purpose programming language. We use it to read data from the computer mouse, and send out to our synthesis model. You can download and install python and pip from [here](https://www.python.org/downloads/). Follow the instructions in the installer.

libraries:
```
pip3 install python-rtmidi
```
```
pip3 install pythonosc
```
```
python -m pip install --upgrade libusb
```

 - ibusb or openUSB (brew install libusb or sudo apt-get install libusb)

 


 
### Installing g++ and c++:
g++ is a compiler for c++ code. We need it to build the c++ source code. [Here](https://www.cs.odu.edu/~zeil/cs250PreTest/latest/Public/installingACompiler/) you can find how to install g++ for each operating system.


### Installing liblo:
We need a c++ library called liblo. To download and install it follow the instructions in [here](http://liblo.sourceforge.net/README.html).




### installing Mouse Violin:
 - download source code
 - make
 - DONE
 
## How to use:
- attach mouse
- run BowedModel
```
./bin/BowedModel
```
- move mouse or use a violinstick

 
