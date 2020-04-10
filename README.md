# Maker Skills: Mouse Violin 

Musical expression is a bottleneck for imitating an acoustic isntruments with digital synthesis. Apart from fluid dynamics and pitchbends, we are missing out on the instrument dependent characteristics. Such as the expression caused by breath and pressure in a clarinet or the bowing position and velocity in a violin. The combination of persueing these instrument dependent characteristics and defining a framework for expression might just be the solution achieve a realistic imitation of acoustic instruments. This is exactly what we aim to do here. This project explores the possibility of musical expression of a digital violin through the use of a simple object like a computer mouse. 

Software instruments that imitate acoustic instruments have been around for a while now. Altough the research on physical modeling of instruments stretches far beyond musical applicability, some interesting vsts, libraries and tools have been developed to put to use these ideas. One of those libraries is [The Synthesis ToolKit in C++ (STK)](https://ccrma.stanford.edu/software/stk/ "The Synthesis ToolKit in C++ (STK)"). For an in depth overview of how this physical modelling works, it is highly recommended to browse through the STK website and source code.

<video width="320" height="240" controls>
  <source type="video/mp4" src="Demo.mp4">
</video>
 

## Installation

To install this software you will need first need to install a collection of programming languages and compilers. This does not only allow you to use the software, but also provides the possibility to research and adapt it to your likings.

### Installing Python, PIP, and libraries:

Python is an interpreted, high-level, general-purpose programming language. We use it to read data from the computer mouse, and send out to our synthesis model. You can download and install python and pip from [here](https://www.python.org/downloads/). Follow the instructions in the installer.

Next we need to install a few python libraries:
- rtmidi
- pythonosc
- libusb

Enter the following lines of code in cmd for windows of terminal on osx/linux.
```
pip3 install python-rtmidi
```
```
pip3 install pythonosc
```
```
pip3 install libusb
```


 
### Installing g++ and c++:
g++ is a compiler for c++ code. We need it to build the c++ source code. [Here](https://www.cs.odu.edu/~zeil/cs250PreTest/latest/Public/installingACompiler/) you can find how to install g++ for each operating system.


### Installing liblo:
We need a c++ library called liblo. To download and install it follow the instructions in [here](http://liblo.sourceforge.net/README.html).




### installing Mouse Violin:
Now you should be set to compile the source code. To do this:
 - Download the source code from this repository
 - cd to the location of the source code on your drive
 - Enter the following line in cmd or the terminal:
 ```
 make
 ``` 
## How to use:
Now you are ready to run the program, so:
- Attach a computer mouse
- Run BowedModel with the following command in cmd or terminal. Make sure you cd inside the directory of the sourcecode.
```
./bin/BowedModel
```
- Now move mouse or use a violinbow, and enjoy!


