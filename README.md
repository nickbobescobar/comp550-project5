# comp550-project5
SAT Plan for Sokoban on Ice problem

## 1. Visualization

### 1.1 Domain File

The domain files are organized in the following format:

size [map-size-x] [map-size-y] 
g [goal-x] [goal-y]
r [robot-starting-x] [robot-starting-y]
movable
[box-0-x] [box-0-y]
[box-1-x] [box-1-y]
...
obstacle
[obstacle-0-x] [obstacle-0-y]
[obstacle-1-x] [obstacle-1-y]
...
end

Make sure the format is followed so the TA could verify your work. 


## 2. Z3

### 2.1 Installation

First, install git. On the virtual machine, type

$ sudo apt-get install git

Then, get z3 using 

$ git clone https://github.com/Z3Prover/z3.git

Follow instructions in z3/README to install z3 (method 2 works on the virtual machine)

### 2.2 Examples

There is a z3 example within the files provided for this project. Type

$make z3_example

to build. This example uses z3 to verify deMorgan's Rule. More examples on using z3 within c++ can be found in the z3 folder under examples/c++.




