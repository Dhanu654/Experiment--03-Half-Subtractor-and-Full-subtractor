## Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor and Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure

![Screenshot 2024-01-02 203533](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/139704ff-c641-4811-a519-9e5780de4dd1)

### Program:
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
~~~
Developed by: Dhanusya K
~~~
RegisterNumber:  23006651
# HALF SUBTRACTOR:
![Screenshot 2024-01-02 201600](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/f931e7b1-812b-4912-ba5f-20a38c345359)

# FULL SUBTRACTOR:
![Screenshot 2024-01-02 201544](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/1af8c9ff-b68c-4449-ac2d-ca90603a0ca5)



# Output:
# Truthtable:
# HALF SUBTRACTOR:
![Screenshot 2024-01-02 201657](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/bd2892f1-2ff8-4447-a092-8b43c3a93ebc)
# FULL SUBTRACTOR:
![Screenshot 2024-01-02 201643](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/c764e5ef-e773-4787-83b5-5e4f958a19dd)



### RTL realization:
# HALF SUBTRACTOR:
![Screenshot 2024-01-02 201631](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/3211a998-2b7b-4b27-9a9a-3e22c547f895)

# FULL SUBTRACTOR:
![Screenshot 2024-01-02 201615](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/ca45187a-4642-43e2-8aea-b1432f1580e2)


## Timing diagram
# HALF SUBTRACTOR:
![Screenshot 2024-01-02 201834](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/0f8be844-3922-4f36-b2a5-33ba06cc3e61)
# FULL SUBTRACTOR:
![Screenshot 2024-01-02 201818](https://github.com/Dhanu654/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514965/502d59e0-d8a3-43b9-8a21-6f17518aad2f)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
