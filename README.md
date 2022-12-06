# Project Information

## Introduction

Milu is an efficient and flexible C mutation testing tool designed for
both first order and highe order mutation testing. The name 'Milu' is
from a deer composed of four other animals. It has a horse's head, a
deer's antlers, a donkey's body and a cow's hooves.


## Compilation in Ubuntu

- sudo apt-get install build-essential libglib2.0-dev llvm libclang-dev
- git clone https://github.com/Milu
- cd Milu
- make

## Usage 
- ./bin/milu -f func.txt src.c 
NB: src.c need to be processed by gcc -E, func.txt contains a list of names of the functions under test

- ./bin/milu -? (to show options)

## Examples

Before to use the examples, you should compile the code. When you compile the code, a folder "bin" will be created. After that you can run the examples.

To run:

```sh
$ sh run.sh
```
