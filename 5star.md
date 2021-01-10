## Vending Machine

## **Rule:** Vending Machine with 5 Star: 5 Rupees, 10 Rupees and 20 Rupees Chocolates and input denomination is {5, 10, 20}




## **DFA: Formal Representation**

## Possible States Q: {S0,S1,S2,S3,S4}


## Input Σ: {5,10,20}

## δ:  Transition Table
Current State | Symbol Read | State To Go
--------------|-------------|------------
 S0 | 5 | S1(F)
 S0| 10 | S2(F)
S0 | 20 |S4(F)
S1|5|S2(F)
S1|10|S3
S2|5|S3
S2|10|S4(F)
S3|5|S4 (F)



## Initial/Start State q0: S0

## Final/Accept  State F: {S1,S2,S4}

## **DFA Diagram for Naming Variables**

![Dfa](dia1.png)