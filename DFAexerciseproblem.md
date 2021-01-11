## 1.Create DFA for (ab*) including Empty String   
soluton:  
**DFA formal representation**   
DFA=(Q,∑,δ,qo,F)  
* Q=Number of states  
Q={q0,q1,q2,q3}  
* ∑=Number of inputs  
* Ɛ=Represent empty string
∑={ Ɛ,a,b}   
* qo=starting state  
qo={q0}     
* F=final state  
F={q0,q1}   
 * δ=Transition Table  

Current state | Symbol read | State to go
---------|----------|---------
 q0 | Ɛ | q0(Accept)
 q0 | a | q1(Accept)
 q1 | b | q1(Accept) 
q0  | b | q2
q1  | a | q3  
  
## 2.Create DFA for (aa)* including Empty String  
soluton:  
**DFA formal representation**   
DFA=(Q,∑,δ,qo,F)  
* Q=Number of states  
Q={q0,q1}  
* ∑=Number of inputs  
* Ɛ=Represent empty string  
∑={ Ɛ,a}   
* qo=starting state  
qo={q0}     
* F=final state  
F={q0}   
* δ=Transition Table  

Current state | Symbol read | State to go
---------|----------|---------
 q0 | Ɛ | q0(Accept)
 q0 | a | q1
 q1 | a | q0(Accept)   
   
## 3.Create DFA for (ab)* including Empty String   
soluton:  
**DFA formal representation**   
DFA=(Q,∑,δ,qo,F)  
* Q=Number of states  
Q={q0,q1,q2,q3}  
* ∑=Number of inputs  
* Ɛ=Represent empty string
∑={ Ɛ,a,b}   
* qo=starting state  
qo={q0}     
* F=final state  
F={q0}   
* δ=Transition Table  

Current state | Symbol read | State to go
---------|----------|---------
 q0 | Ɛ | q0(Accept)
 q0 | a | q1
 q1 | b | q0(Accept) 
q0  | b | q2
q1  | a | q3  
  
   
## 4.Create DFA for (a* b*)      
soluton:  
**DFA formal representation**   
DFA=(Q,∑,δ,qo,F)  
* Q=Number of states  
Q={q0}  
* ∑=Number of inputs  
* Ɛ=Represent empty string
∑={ Ɛ,a,b}   
* qo=starting state  
qo={q0}     
* F=final state  
F={q0}   
* δ=Transition Table  

Current state | Symbol read | State to go
---------|----------|---------
 q0 | Ɛ | q0(Accept)
 q0 | a | q0(Accept)
 q0 | b | q0(Accept)   
   
## 5.Create DFA for (a+b*c)   
soluton:  
**DFA formal representation**   
DFA=(Q,∑,δ,qo,F)  
* Q=Number of states  
Q={q0,q1,q2,q3,q4}  
* ∑=Number of inputs  
* Ɛ=Represent empty string
∑={Ɛ,a,b,c}   
* qo=starting state  
qo={q0}     
* F=final state  
F={q2}   
* δ=Transition Table  

Current state | Symbol read | State to go
---------|----------|---------
 q0 | a | q1  
 q1 | b,Ɛ|q1
 q1 | c | q2(Accept)
 q2 | a | q1 
q2  | b,c | q4    
  
## 6.Create DFA for (a* b+c*)   
soluton:  
**DFA formal representation**   
DFA=(Q,∑,δ,qo,F)  
* Q=Number of states  
Q={q0,q1,q2,q3}  
* ∑=Number of inputs  
* Ɛ=Represent empty string
∑={Ɛ,a,b,c}   
* qo=starting state  
qo={q0}     
* F=final state  
F={q1}   
 δ=Transition Table  

Current state | Symbol read | State to go
---------|----------|---------
 q0 | a,Ɛ | q1  
 q0 | b|q1
 q0 | c,Ɛ | q1(Accept)
 q0 | c | q2 
q1  | b,c | q4 
q1  | a | q0      

![DFA1](exe1.png)
![DFA1](exe2.png)  
![DFA1](exe3.png)  
![DFA1](exe4.png)  
![DFA1](exe5.png)  
![DFA1](exe6.png)
  