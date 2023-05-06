bases on these video : https://www.youtube.com/watch?v=FI6j5QZNVx0 https://www.youtube.com/watch?v=4Caxyh0zt_o
related : [[set theory]] 
#sumarize  
A relation R on a set X is a subset of A 
if (a,b)$\in$ R , we write xRy
"x is realted to y"


xGy : x is greater than y . (x,y)$\in$ Z 
(4,3) 4G3 G(4,3) : check 

## reflexive 
$\forall$x  xRy 
![[ref.PNG]]
A relation R on set A is called reflexive if (a,a)$\in$ R for every element a $\in$ A . In other words , $\forall$ a((a,a)$\in$R)
Example : 
- let A = {1,2,3,4}
- R1 = {(1,1),(2,2),(3,3),(4,4)} 
- relation R1 is reflexice because it containt all ordered pairs of the form (a,a) for every element a$\in$ A i.e , R1 has (1,1) (2,2) (3,3) (4,4)
### irreflexive relation 
A relation R on set A is called irreflexive if $\forall$a $\in$ A , (a,a) $\notin$ R .
example : 
- A = {1,2,3,4}
- R3  = {(1,2),(2,1),(3,3) ,(4,4)} is not irreflexive because (3,3) and (4,4) is there in R3 

## symmetric 
$\forall$x $\forall$y xRy -> yRx 
![[sym.PNG]]
A relation R on a set A is called symmetric if  (b,a) $\in$ R hold then when (a,b) $\in$ R for all a,b $\in$ A 
in other words , relation R on a set A is symmetric if  $\forall$a$\forall$b((a,b)$\in$ R -> (b,a)$\in$ R)
Example : 
- relation R5 = {(1,1) , (1,2 ), (2,1) , ( 2,2)} is symmetric because for every (a,b )$\in$ R5  ( b,a )$\in$ R5 
- like (1,2) ( 2,1) is in R5 
- there is no need to check for (1,1) ,( 2,2 )
### anti symmetric realtion 
A relation R on a set A is called antisysmmetric if $\forall a \forall b ((a,b) \in R \land (b,a) \in R )->(a=b)$
Example : relation R7 = {(1,1)(2,1)} on set A is antisymmetric because (2,1) is in R7 but (1,2) is not in R7 


## transitive 
$\forall$x $\forall$y xRy $\land$ xyRz -> xRz 

![[d.PNG]]
A relation R on set A is called transitive if $\forall a $\forall b \forall c \forall a (((a,b)\in R\land (b,c)\in R)->(a,c)\in R)$
example : 
- A = {1,2,3,4}
- R8={(2,1),(3,1) , (3,2),(4,4)}is transitive because (3,2) , (2,1) and ( 3,1) are there in R8
- R9 ={(2,1),(1,3)} is not transitive as ( 2,1) and (1,3) are there in R9 but there is no (2,3) in realtion R9 
## Asymmtric Relation : 
A raltion R on a set A is called asymmetric if $\forall a \forall b ((a,b)\in R -> (b,a)\notin R)$
example : 
- A {1,2,3,4}
- R10 = {(1,1),(1,2),(1,3)} is not asymmetric realtion because of (1m)

## definition 
let A and B be two sets. A binary relation R from A to B is a subset of AXB OR R $\subset$ AXB 
AXB  = {(a,b)| a $\in$ A and b$\in$ B}
usually we use the notation aRb to denote (a,b)$\in$ R 
![[a.PNG]]
A = {1,2,3} and B ={0,1,2,4}
AXB = {(1,0), (1,1), (1,2),(1,4), (2,0)...}}
Let say R is the relation where (a,b )$\in$ R if and only if a=b then R = {(1,1),(2,2)} and R $\subset$ AXB 
### relation from a set to itself 
A relation on a set A is a relation from A to A. 
example : Let R  ={(a,b)|a divides b}
A = {1,2,3,4,5,6}
R = {(1,1), {1,2},(1,3) ... (4,4), (5,5) ,(6,6 )}
![[relation.PNG]]




