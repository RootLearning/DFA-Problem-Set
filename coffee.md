## Coffee Machine with 4 different drinks:

## **Rule:**   Tea – 10 Rupees, Coffee – 15 Rupees, Green Tea – 20 Rupees, Hot Chocolate – 30 Rupees and input denomination is {5, 10, 20}



## **DFA: Formal Representation**

## Possible States Q: {S0,S1,S2,S3,S4,S5,S6}

## Input Σ: {5,10,20}

## δ:  Transition Table
Current State | Symbol Read | State To Go
--------------|-------------|------------
 S0|5 | S1
S0| 10 | S2(F)
S0| 20| S6(F)
S1|5  |S2(F)
S1|10|S3(F)
S1|20|S5
S2|5|S3(F)
S2|10|S4(F)
S2|20|S6(F)
S3|5|S4(F)
S3|10|S5
S4|5|S5
S4|10|S6(F)
S5|5|S6(F)


## Initial/Start State q0: S0

## Final/Accept  State F: {S2,S3,S4,S6}

## **DFA Diagram for Naming Variables**
![dfa](dia2.png)