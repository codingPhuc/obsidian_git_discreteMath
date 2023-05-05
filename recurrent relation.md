bases on this video :[RECURRENCE RELATIONS - DISCRETE MATHEMATICS - YouTube](https://www.youtube.com/watch?v=eAaP4XaB8hM)
#sumarize 
 number in a sequence depend on the previous number
- fibonacci sequence and its formal definition An = An-1 + An-2 (A0=0 , A1=1) n >= 2 
- geometric progression An = 2An-1(A0 =3)

## formula
An - A(n-1) = K   , A0 =C  n>=1 
convert $a_n - a_{n-1} = k$ 
![[the resond why.PNG]]
to An = A0 + $\sum_{i=1}^{n} k$ 
example 
- given A0 = 0 
- n>=1 
- An -A(n-1) = 2n  
An = 0+ $\sum_{i=1}^{n} 2n$= 2$\sum_{i=1}^{n} n$ = 2 (n )(n+1) /2 



## sloving  re currence Relation 
we want an easy equation to find the value of any term 
[sloving the formula mean finding the formula $a_n =?$ ]
$a_n = 3a_{n-1}$
$a_0 = 7$  
-> $a_n = 7 *3^n$ 
another example 
$a_n - a_{n-1}= k /a_0 =c$ 
$a_n = C + \sum_{i=1}^{n}k$ 
### hard problem 
$a_n - a_{n-1} - 6*a_{n-2} =0$ where $a_0 =1 , a_1=8$
$r^n - r^{n-1} - 6^{n-2}=0$
$r^2 - r^{} - 6^{}=0$ divide it by the $r^{r-2}$ 



