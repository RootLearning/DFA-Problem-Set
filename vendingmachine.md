## 2. Coffee Machine with Four Different Drinks: Tea – 10 Rupees, Coffee – 15 Rupees,
Green Tea – 20 Rupees, Hot Chocolate – 30 Rupees and input denomination is {5, 10, 20}  
Soluton:  
**DFA formal representation**   
DFA=(Q,∑,δ,qo,F)  
* Q=Number of states  
Q={q0,q1,q2,q3,q4}  
* ∑=Number of inputs  
* Ɛ=Represent empty string
∑={5,10,20}   
* qo=starting state  
qo={q0}     
* F=final state  
F={q1,q2,q4}   
 * δ=Transition Table  

Current state | Symbol read | State to go
---------|----------|---------
 q0 | 5 | q1(Accept) 
 q1 | 5 | q2(Accept) 
 q2 | 5 | q3
q3 | 5 | q4(Accept) 
q0 | 10 | q2(Accept) 
q2 | 10 | q4(Accept)
q1 | 10 | q3
q0 | 20 | q4(Accept) 
 
![DFA](vendingmachine.png)
  