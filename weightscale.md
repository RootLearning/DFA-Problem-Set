## 1.Coin based Weighing Scale: Get Weight – 2 Rupees and input denomination is {1, 2}  
Soluton:  
**DFA formal representation**   
DFA=(Q,∑,δ,qo,F)  
* Q=Number of states  
Q={q0,q1,q2,q3}  
* ∑=Number of inputs  
* Ɛ=Represent empty string
∑={1,2}   
* qo=starting state  
qo={q0}     
* F=final state  
F={q2}   
 * δ=Transition Table  

Current state | Symbol read | State to go
---------|----------|---------
 q0 | 1 | q1
 q1 | 1 | q2(Accept) 
 q0 | 2 | q2(Accept) 
q1 | 2 | q3  
  